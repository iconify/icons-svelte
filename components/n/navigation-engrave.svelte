<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uxuqlo1po.css';
import '../../css/s/sq_axr2cd.css';
import '../../css/q/qbtperb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uxuqlo1po"/><path class="sq_axr2cd wm-shadow"/><path class="qbtperb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:navigation-engrave" {...props}></Icon>
