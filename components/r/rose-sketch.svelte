<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/awf5bhbxs.css';
import '../../css/k/kfz5yrb5e.css';
import '../../css/z/z3te8sbzk.css';
import '../../css/u/uikytvy5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="awf5bhbxs wm-deco"/><path class="kfz5yrb5e wm-k"/><path class="wm-k z3te8sbzk"/><path class="uikytvy5m wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rose-sketch" {...props}></Icon>
