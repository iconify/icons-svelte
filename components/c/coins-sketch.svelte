<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kwkco47_d.css';
import '../../css/k/k89hfgloi.css';
import '../../css/z/zoiwa9bvm.css';
import '../../css/g/g0w_m7lbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kwkco47_d"/><path class="k89hfgloi wm-a"/><path class="wm-k zoiwa9bvm"/><path class="g0w_m7lbe wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:coins-sketch" {...props}></Icon>
