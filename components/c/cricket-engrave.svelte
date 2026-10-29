<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u6co3bc3l.css';
import '../../css/u/usvv9bqzp.css';
import '../../css/b/b2j8s_bbd.css';
import '../../css/j/jjivkrbpv.css';
import '../../css/x/xcez03_th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u6co3bc3l wm-k"/><path class="usvv9bqzp wm-a"/><path class="b2j8s_bbd wm-shadow"/><path class="jjivkrbpv wm-k"/><path class="wm-a xcez03_th"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cricket-engrave" {...props}></Icon>
