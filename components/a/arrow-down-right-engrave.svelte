<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c93vbchsa.css';
import '../../css/t/t1mrv2pln.css';
import '../../css/a/a9x2q_n_h.css';
import '../../css/o/ouu4wvpmp.css';
import '../../css/y/y5lva8w-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c93vbchsa wm-k"/><path class="t1mrv2pln wm-a"/><path class="a9x2q_n_h wm-shadow"/><path class="ouu4wvpmp wm-k"/><path class="wm-a y5lva8w-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-down-right-engrave" {...props}></Icon>
