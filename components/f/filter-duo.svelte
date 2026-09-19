<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4gi0yizr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="f4gi0yizr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:filter-duo" {...props}></Icon>
