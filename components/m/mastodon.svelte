<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/ggxvnybxb.css';
import '../../css/t/twcexwbvp.css';
import '../../css/f/fdfttbm9b.css';
import '../../css/y/yw-sn55so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":61,"height":65};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG2wvHBcLd)" class="ggxvnybxb"/><path class="twcexwbvp"/><defs><linearGradient id="SVG2wvHBcLd" x1="30.5" x2="30.5" y1="0" y2="65" gradientUnits="userSpaceOnUse"><stop class="fdfttbm9b"/><stop offset="1" class="yw-sn55so"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mastodon" {...props}></Icon>
