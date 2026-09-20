<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sll_zg-uo.css';
import '../../css/c/ccqymhpos.css';
import '../../css/l/l6xvejonm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG5mdS0brk" x1="2136.942" x2="2363.435" y1="125.81" y2="125.81" gradientTransform="rotate(180 1244.122 256.5)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sll_zg-uo"/><stop offset="1"/></linearGradient><path fill="url(#SVG5mdS0brk)" class="ccqymhpos"/><path class="l6xvejonm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:interactive-brokers-dark" {...props}></Icon>
