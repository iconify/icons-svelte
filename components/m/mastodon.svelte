<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdfttbm9b.css';
import '../../css/y/yw-sn55so.css';
import '../../css/a/ak99vsb_d.css';
import '../../css/n/n48w_vb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGstIU2dWl" x1="256" x2="256" y2="512" gradientUnits="userSpaceOnUse"><stop offset="0" class="fdfttbm9b"/><stop offset="1" class="yw-sn55so"/></linearGradient><path fill="url(#SVGstIU2dWl)" class="ak99vsb_d"/><path class="n48w_vb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mastodon" {...props}></Icon>
