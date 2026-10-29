<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qjvj2ib0t.css';
import '../../css/t/tzhb1vbig.css';
import '../../css/w/wnz0iqbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qjvj2ib0t"/><path class="tzhb1vbig wm-a"/><path class="wnz0iqbyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-candlestick-duo" {...props}></Icon>
