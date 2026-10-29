<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/imw0pubej.css';
import '../../css/m/m2s_ux-ta.css';
import '../../css/e/eoa1yhbin.css';
import '../../css/w/wa7muobyt.css';
import '../../css/s/sukohubkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="imw0pubej wm-k"/><path class="m2s_ux-ta wm-a"/><path class="eoa1yhbin wm-shadow"/><path class="wa7muobyt wm-k"/><path class="sukohubkj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-bar-engrave" {...props}></Icon>
