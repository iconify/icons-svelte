<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mstq20lgc.css';
import '../../css/o/ofe42gb8z.css';
import '../../css/m/mzfc7hb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="mstq20lgc"/><path class="ofe42gb8z"/><path class="mzfc7hb3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:journal-medical" {...props}></Icon>
