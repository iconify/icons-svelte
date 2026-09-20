<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vwchn3tyd.css';
import '../../css/c/ctbp2ybpi.css';
import '../../css/v/v3k4esbvy.css';
import '../../css/k/kmhx_lrvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vwchn3tyd"/><path class="ctbp2ybpi"/><circle class="v3k4esbvy"/><path clip-rule="evenodd" class="kmhx_lrvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:cake" {...props}></Icon>
