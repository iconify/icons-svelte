<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf7z-yejv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yf7z-yejv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-like" {...props}></Icon>
