<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pcrb767dm.css';
import '../../css/o/ofbe2g9yf.css';
import '../../css/k/k25u9dy7m.css';
import '../../css/s/s42c10bcn.css';
import '../../css/w/wpyzi_bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pcrb767dm"/><path class="ofbe2g9yf wm-k"/><path class="k25u9dy7m wm-s"/><path class="s42c10bcn wm-k"/><path class="wm-s wpyzi_bol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:moon-star-sketch" {...props}></Icon>
