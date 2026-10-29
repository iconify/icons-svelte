<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p5dvptbly.css';
import '../../css/d/domdhwbzo.css';
import '../../css/k/kqp_we97z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p5dvptbly"/><path class="domdhwbzo wm-a"/><path class="kqp_we97z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:carrot-duo" {...props}></Icon>
