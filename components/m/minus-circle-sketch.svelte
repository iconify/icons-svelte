<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/otbqr_zzw.css';
import '../../css/z/z-cabbcfr.css';
import '../../css/q/qcxu_iduf.css';
import '../../css/t/tt67h0p8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="otbqr_zzw wm-k"/><path class="wm-k z-cabbcfr"/><path class="qcxu_iduf wm-k"/><path class="tt67h0p8u wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minus-circle-sketch" {...props}></Icon>
