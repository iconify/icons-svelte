<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u_jv868wi.css';
import '../../css/a/ai8_c8bmq.css';
import '../../css/j/j44_jlbcg.css';
import '../../css/l/lhr7mp78x.css';
import '../../css/z/z5pfo_ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u_jv868wi wm-k"/><path class="ai8_c8bmq wm-a"/><path class="j44_jlbcg wm-shadow"/><path class="lhr7mp78x wm-k"/><path class="wm-a z5pfo_ber"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-snow-engrave" {...props}></Icon>
