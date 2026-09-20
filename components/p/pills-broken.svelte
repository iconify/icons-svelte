<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hrkp-tbak.css';
import '../../css/v/vr39ulzpl.css';
import '../../css/h/h0g48wbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hrkp-tbak"/><path class="vr39ulzpl"/><path class="h0g48wbnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pills-broken" {...props}></Icon>
