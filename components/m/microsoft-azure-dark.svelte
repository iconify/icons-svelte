<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4jryvres.css';
import '../../css/r/rw5c_lizo.css';
import '../../css/y/yw8ns2ibw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4jryvres"/><linearGradient id="SVGEsmpMgIR" x1="395.32" x2="263.097" y1="89.142" y2="479.761" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="rw5c_lizo"/></linearGradient><path fill="url(#SVGEsmpMgIR)" class="yw8ns2ibw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-azure-dark" {...props}></Icon>
