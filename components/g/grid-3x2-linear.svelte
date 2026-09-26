<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qioz3pgou.css';
import '../../css/x/xdk9_oksp.css';
import '../../css/r/rma5_ql1e.css';
import '../../css/b/bfsv7cc4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qioz3pgou"/><path class="xdk9_oksp"/><path class="rma5_ql1e"/><path class="bfsv7cc4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-3x2-linear" {...props}></Icon>
