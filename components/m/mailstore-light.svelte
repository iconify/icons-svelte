<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/f/fzo_evvda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG47nHkwpy" x1="102.123" x2="456.589" y1="102.123" y2="456.589" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG47nHkwpy)" class="fzo_evvda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailstore-light" {...props}></Icon>
