<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ed0pqxdzw.css';
import '../../css/j/jolt8cvri.css';
import '../../css/i/ilyiwztto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ed0pqxdzw"/><path class="jolt8cvri"/><path class="ilyiwztto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:camera-reels" {...props}></Icon>
