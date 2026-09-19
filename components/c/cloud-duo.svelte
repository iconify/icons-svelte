<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzgwfsg3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rzgwfsg3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cloud-duo" {...props}></Icon>
