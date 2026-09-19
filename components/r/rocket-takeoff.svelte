<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/szatyqnji.css';
import '../../css/q/qlmmw0bib.css';
import '../../css/y/yvaopobve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="szatyqnji"/><path class="qlmmw0bib"/><path class="yvaopobve"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:rocket-takeoff" {...props}></Icon>
