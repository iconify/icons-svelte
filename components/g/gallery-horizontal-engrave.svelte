<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cbs9hpbzb.css';
import '../../css/g/gxobe3bsj.css';
import '../../css/k/kdh9_zb5j.css';
import '../../css/o/omtqkcbfk.css';
import '../../css/o/od38u2bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cbs9hpbzb wm-k"/><path class="gxobe3bsj wm-a"/><path class="kdh9_zb5j wm-shadow"/><path class="omtqkcbfk wm-k"/><path class="od38u2bjg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gallery-horizontal-engrave" {...props}></Icon>
