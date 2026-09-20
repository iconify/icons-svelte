<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zi7qjjbiy.css';
import '../../css/d/d3r2wb0it.css';
import '../../css/k/k4l4-797u.css';
import '../../css/u/ul5rc3bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zi7qjjbiy"/><path class="d3r2wb0it"/><path class="k4l4-797u"/><path class="ul5rc3bsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:dna" {...props}></Icon>
