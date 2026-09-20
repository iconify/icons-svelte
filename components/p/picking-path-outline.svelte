<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvbbt4bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wvbbt4bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:picking-path-outline" {...props}></Icon>
