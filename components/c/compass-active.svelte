<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/ryzdgqbmc.css';
import '../../css/u/u0nnfubxp.css';
import '../../css/q/qrvidobik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ryzdgqbmc"/><path clip-rule="evenodd" class="u0nnfubxp"/><path class="qrvidobik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:compass-active" {...props}></Icon>
