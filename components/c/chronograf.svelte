<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exqc7kwxs.css';
import '../../css/v/vsr0hw0fo.css';
import '../../css/r/rrvqfdczg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":140,"height":140};
const content = `<linearGradient id="SVGKQj6QcUj" x1="63.166" x2="107.666" y1="62.628" y2="110.628" gradientUnits="userSpaceOnUse"><stop offset="0" class="exqc7kwxs"/><stop offset="1" class="vsr0hw0fo"/></linearGradient><path fill="url(#SVGKQj6QcUj)" class="rrvqfdczg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chronograf" {...props}></Icon>
