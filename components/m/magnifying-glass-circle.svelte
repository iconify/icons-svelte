<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q95w-kbvl.css';
import '../../css/l/l_pfsmopg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="q95w-kbvl"/><path clip-rule="evenodd" class="l_pfsmopg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:magnifying-glass-circle" {...props}></Icon>
