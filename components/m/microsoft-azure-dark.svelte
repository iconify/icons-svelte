<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4jryvres.css';
import '../../css/r/rw5c_lizo.css';
import '../../css/y/yw8ns2ibw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4jryvres"/><linearGradient id="SVGzF0JrCLX" x1="395.3" x2="263.1" y1="89.1" y2="479.8" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="rw5c_lizo"/></linearGradient><path fill="url(#SVGzF0JrCLX)" class="yw8ns2ibw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-azure-dark" {...props}></Icon>
