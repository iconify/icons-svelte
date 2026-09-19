<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbt4iosku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<rect transform="rotate(45 40 12)" class="mbt4iosku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:diamond-1-bold" {...props}></Icon>
