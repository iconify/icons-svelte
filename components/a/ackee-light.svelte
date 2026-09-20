<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/i/iycln-b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG5pdNacpA" x1="74.981" x2="437.019" y1="74.981" y2="437.019" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><circle fill="url(#SVG5pdNacpA)" class="iycln-b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ackee-light" {...props}></Icon>
