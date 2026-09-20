<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cx2a49bhn.css';
import '../../css/u/u8qhtt3pv.css';
import '../../css/q/qxw3kzbst.css';
import '../../css/q/q60im6_xs.css';
import '../../css/h/h4r2f10fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cx2a49bhn"/><path class="u8qhtt3pv"/><path class="qxw3kzbst"/><path class="q60im6_xs"/><path class="h4r2f10fp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:binoculars-line-duotone" {...props}></Icon>
