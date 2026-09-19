<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j84_xvb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="j84_xvb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-stand-outline" {...props}></Icon>
