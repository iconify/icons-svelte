<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4d1rx7fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="w4d1rx7fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bars-offset-2-duo" {...props}></Icon>
