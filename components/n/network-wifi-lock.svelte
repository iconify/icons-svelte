<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh756ubkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":504,"height":408};
const content = `<path class="sh756ubkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:network-wifi-lock" {...props}></Icon>
