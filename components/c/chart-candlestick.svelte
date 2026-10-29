<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/i/ikplvmbos.css';
import '../../css/r/racm5fbpm.css';
import '../../css/d/d2xmu7b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="ikplvmbos"/><path class="racm5fbpm"/><path class="d2xmu7b2s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chart-candlestick" {...props}></Icon>
