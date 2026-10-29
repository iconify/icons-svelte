<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dqywfr4sz.css';
import '../../css/o/oj5c48bry.css';
import '../../css/t/tf3d3bb_b.css';
import '../../css/z/zoxatjh8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dqywfr4sz"/><path class="oj5c48bry wm-k"/><path class="tf3d3bb_b wm-k"/><path class="wm-a zoxatjh8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chocolate-box-sketch" {...props}></Icon>
