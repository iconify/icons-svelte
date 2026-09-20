<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij2x_72vy.css';
import '../../css/a/an3wb-bzz.css';
import '../../css/c/ckusvhbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="ij2x_72vy"><path class="an3wb-bzz"/><path class="ckusvhbps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:fast-reverse-button" {...props}></Icon>
