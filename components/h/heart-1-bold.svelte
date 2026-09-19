<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl08a40-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cl08a40-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-1-bold" {...props}></Icon>
