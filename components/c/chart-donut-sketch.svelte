<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lggc47b1l.css';
import '../../css/h/hfmjco30i.css';
import '../../css/j/j2lty-60i.css';
import '../../css/s/shw1frbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lggc47b1l wm-k"/><path class="hfmjco30i wm-a"/><path class="j2lty-60i wm-k"/><path class="shw1frbig wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-donut-sketch" {...props}></Icon>
