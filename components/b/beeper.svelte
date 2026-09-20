<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs666di4s.css';
import '../../css/x/xaigl9buy.css';
import '../../css/k/k0hbd4wrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGx6uZrebc" x1="475.208" x2="33.584" y1="392.219" y2="137.247" gradientUnits="userSpaceOnUse"><stop offset="0" class="gs666di4s"/><stop offset="1" class="xaigl9buy"/></linearGradient><path fill="url(#SVGx6uZrebc)" class="k0hbd4wrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beeper" {...props}></Icon>
