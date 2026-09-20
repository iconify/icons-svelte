<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywztcab3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ywztcab3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:calm-face-in-circle-outline" {...props}></Icon>
