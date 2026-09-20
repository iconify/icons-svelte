<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wifo-cb2s.css';
import '../../css/w/wqp-bwb_c.css';
import '../../css/d/dm_mfnb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGwONFndEi" x1="0" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="wifo-cb2s"/><stop offset="1" class="wqp-bwb_c"/></linearGradient><path fill="url(#SVGwONFndEi)" class="dm_mfnb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsandbox" {...props}></Icon>
