<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b5oqxccsk.css';
import '../../css/n/n_g0fjydz.css';
import '../../css/f/f9d6qcb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b5oqxccsk"/><path class="n_g0fjydz"/><path class="f9d6qcb-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:clipboard-note" {...props}></Icon>
