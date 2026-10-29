<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/btaeqlyar.css';
import '../../css/v/vtc093b0f.css';
import '../../css/o/o-4nchs_d.css';
import '../../css/e/e_w_3-pqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="btaeqlyar"/><path class="vtc093b0f wm-a"/><path class="o-4nchs_d wm-k"/><path class="e_w_3-pqg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:badge-check-sketch" {...props}></Icon>
