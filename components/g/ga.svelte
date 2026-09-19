<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yrncfdc7x.css';
import '../../css/k/kowma_bmi.css';
import '../../css/t/t5lqdhfmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":225};
const content = `<g class="ft5dv1b6b"><path class="yrncfdc7x"/><path class="kowma_bmi"/><path class="t5lqdhfmd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:ga" {...props}></Icon>
