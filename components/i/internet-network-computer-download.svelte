<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiku0v4qh.css';
import '../../css/z/z4a7i9bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yiku0v4qh"/><path class="z4a7i9bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:internet-network-computer-download" {...props}></Icon>
