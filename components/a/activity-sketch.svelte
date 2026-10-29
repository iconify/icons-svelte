<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i62_4pb6q.css';
import '../../css/n/n-y_o-btm.css';
import '../../css/c/cfe6kwbgv.css';
import '../../css/y/yvr-gzb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i62_4pb6q wm-k"/><path class="n-y_o-btm wm-deco"/><path class="cfe6kwbgv wm-k"/><path class="wm-deco yvr-gzb_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:activity-sketch" {...props}></Icon>
