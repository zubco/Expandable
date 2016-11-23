use_frameworks!
platform :ios, '10.0'

workspace 'Expandable.xcworkspace'

def shared_pods
    pod 'R.swift'
    pod 'RxSwift', '~> 3.0.0-rc.1'
    pod 'RxCocoa', '~> 3.0.0-rc.1'
    pod 'RxDataSources', '~> 1.0'
end

target 'Expandable' do
    platform :ios, '10.0'
    shared_pods
    project 'Expandable.xcodeproj'
end
