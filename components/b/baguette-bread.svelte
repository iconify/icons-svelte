<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyf3f-bfc.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/l/lc32bsb7m.css';
import '../../css/g/gpkkzdb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="eyf3f-bfc"/><g class="ij2x_72vy"><path class="lc32bsb7m"/><path class="gpkkzdb8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:baguette-bread" {...props}></Icon>
