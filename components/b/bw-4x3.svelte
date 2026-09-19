<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/fdv_t3ltl.css';
import '../../css/v/v18c9fbau.css';
import '../../css/b/ba-qp9bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="d2kvgvbvc"><path class="fdv_t3ltl"/><path class="v18c9fbau"/><path class="ba-qp9bir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:bw-4x3" {...props}></Icon>
