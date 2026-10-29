<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/ddrij4byh.css';
import '../../css/u/uy1c6ogkr.css';
import '../../css/p/pt47m9bdk.css';
import '../../css/w/w2na52oxh.css';
import '../../css/o/o_3oriblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ddrij4byh"/><path class="uy1c6ogkr wm-k"/><path class="pt47m9bdk wm-a"/><path class="w2na52oxh wm-k"/><path class="o_3oriblb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mountain-snow-sketch" {...props}></Icon>
