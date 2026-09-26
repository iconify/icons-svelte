<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pxuzj6ljm.css';
import '../../css/c/cnjmecc5c.css';
import '../../css/f/fnlxv3bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pxuzj6ljm"/><path class="cnjmecc5c"/><path clip-rule="evenodd" class="fnlxv3bgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-close-outline" {...props}></Icon>
