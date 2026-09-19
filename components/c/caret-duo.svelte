<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khmi4egos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="khmi4egos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:caret-duo" {...props}></Icon>
