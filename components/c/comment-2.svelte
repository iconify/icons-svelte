<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3q7igb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="d3q7igb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-2" {...props}></Icon>
