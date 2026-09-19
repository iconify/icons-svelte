<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yifwj2bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yifwj2bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:cny" {...props}></Icon>
