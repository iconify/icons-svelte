<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fhuo6fxyk.css';
import '../../css/i/ivj0dyb1p.css';
import '../../css/c/cjivcabhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fhuo6fxyk"/><path class="ivj0dyb1p wm-a"/><path class="cjivcabhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cursor-duo" {...props}></Icon>
