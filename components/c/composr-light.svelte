<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc--wpv5i.css';
import '../../css/f/f-c80ro0i.css';
import '../../css/p/pq9c81bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG2rwPXc2A" x1="287.32" x2="288.868" y1="195.965" y2="194.417" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="f-c80ro0i"/></linearGradient><path fill="url(#SVG2rwPXc2A)" class="pq9c81bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:composr-light" {...props}></Icon>
