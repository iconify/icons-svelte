<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fsii3zsmr.css';
import '../../css/j/j7zbqvg7v.css';
import '../../css/i/ik857bg1p.css';
import '../../css/i/iagn37brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fsii3zsmr"/><path class="j7zbqvg7v wm-a"/><path class="ik857bg1p wm-a"/><path class="iagn37brf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:library-duo" {...props}></Icon>
