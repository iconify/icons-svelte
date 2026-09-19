<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/m/muvtlrodu.css';
import '../../css/d/d03q2nt3l.css';
import '../../css/z/zvtazzblk.css';
import '../../css/t/tu-lmhbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="muvtlrodu"/><circle class="d03q2nt3l"/><path class="zvtazzblk"/><path class="tu-lmhbyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:doughnut" {...props}></Icon>
