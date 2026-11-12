<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjzrp5bve.css';
import '../../css/x/x1ob552sn.css';
import '../../css/l/l3siukbxa.css';
import '../../css/o/ow6yk2bvl.css';
import '../../css/y/y5ivewbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGkyJe5b4p" x1="1124.653" x2="1839.97" y1="-669.315" y2="-669.315" gradientTransform="matrix(.3694 0 0 -.3694 -322.75 -168.2)" gradientUnits="userSpaceOnUse"><stop offset="0" class="pjzrp5bve"/><stop offset="1" class="x1ob552sn"/></linearGradient><path fill="url(#SVGkyJe5b4p)" class="l3siukbxa"/><path class="ow6yk2bvl"/><path class="y5ivewbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-hole" {...props}></Icon>
