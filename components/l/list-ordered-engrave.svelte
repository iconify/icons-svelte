<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oa29y7bly.css';
import '../../css/x/x953aub5i.css';
import '../../css/m/mtbeuljrv.css';
import '../../css/q/qb8r96btl.css';
import '../../css/b/bry1z00iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oa29y7bly wm-k"/><path class="wm-a x953aub5i"/><path class="mtbeuljrv wm-shadow"/><path class="qb8r96btl wm-k"/><path class="bry1z00iu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-ordered-engrave" {...props}></Icon>
