<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d1z7q3bfk.css';
import '../../css/d/d32py0roj.css';
import '../../css/r/rjsiwsb8d.css';
import '../../css/c/c8_qq32sd.css';
import '../../css/f/frvx07aef.css';
import '../../css/h/h4_j_tb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d1z7q3bfk"/><path class="d32py0roj"/><path class="rjsiwsb8d"/><path class="c8_qq32sd"/><path class="frvx07aef"/><path class="h4_j_tb2s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-detect" {...props}></Icon>
