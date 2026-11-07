<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ovw1pubnt.css';
import '../../css/d/d_xp_lbcm.css';
import '../../css/q/q7kvgacmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ovw1pubnt"/><path class="d_xp_lbcm"/><path class="q7kvgacmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-low-line-duotone" {...props}></Icon>
