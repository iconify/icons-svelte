<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d98p024yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="d98p024yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bars-offset-2-bold" {...props}></Icon>
