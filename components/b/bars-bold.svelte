<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8yf2jbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="l8yf2jbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bars-bold" {...props}></Icon>
