<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mzd118pxz.css';
import '../../css/h/hcn_edccn.css';
import '../../css/x/xnodzworh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="mzd118pxz wm-k"/><path class="hcn_edccn wm-a"/><path class="wm-s xnodzworh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:alarm-clock-off-gloss" {...props}></Icon>
