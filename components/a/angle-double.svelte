<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gszn0u93e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gszn0u93e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:angle-double" {...props}></Icon>
