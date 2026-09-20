<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxphk2e7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yxphk2e7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:camera-retro" {...props}></Icon>
