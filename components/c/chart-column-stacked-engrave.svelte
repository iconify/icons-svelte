<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g1l9j8-ir.css';
import '../../css/m/m2s_ux-ta.css';
import '../../css/l/lw_p7hcmh.css';
import '../../css/s/sukohubkj.css';
import '../../css/c/c012e5boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g1l9j8-ir wm-k"/><path class="m2s_ux-ta wm-a"/><path class="lw_p7hcmh wm-shadow"/><path class="sukohubkj wm-a"/><path class="c012e5boc wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-column-stacked-engrave" {...props}></Icon>
