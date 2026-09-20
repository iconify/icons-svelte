<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud9mscb4f.css';
import '../../css/w/wrc732bfl.css';
import '../../css/i/iycln-b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGSRwzPbeE" x1="74.981" x2="437.019" y1="74.981" y2="437.019" gradientUnits="userSpaceOnUse"><stop offset="0" class="ud9mscb4f"/><stop offset="1" class="wrc732bfl"/></linearGradient><circle fill="url(#SVGSRwzPbeE)" class="iycln-b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ackee" {...props}></Icon>
