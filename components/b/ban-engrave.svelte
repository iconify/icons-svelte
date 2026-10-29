<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sfq88wc1b.css';
import '../../css/t/tnz7amgmb.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/r/r4m5x7bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sfq88wc1b wm-k"/><path class="tnz7amgmb wm-shadow"/><path class="wm-k yw4fz_b6b"/><path class="r4m5x7bba wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ban-engrave" {...props}></Icon>
