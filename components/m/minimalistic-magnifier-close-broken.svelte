<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mj_6ev9oe.css';
import '../../css/x/x09loybdy.css';
import '../../css/k/k_wd3t9ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mj_6ev9oe"/><path class="x09loybdy"/><path class="k_wd3t9ba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-close-broken" {...props}></Icon>
