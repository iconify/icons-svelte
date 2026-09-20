<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzrff5bem.css';
import '../../css/o/ogq8t8zoi.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/t/ty0jp0byr.css';
import '../../css/z/zyiv9wvjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xzrff5bem"/><path class="ogq8t8zoi"/><g class="ij2x_72vy"><path class="ty0jp0byr"/><path class="zyiv9wvjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ear-light-skin-tone" {...props}></Icon>
