<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gtk28sbwi.css';
import '../../css/h/hme0rabnh.css';
import '../../css/r/req8k0dco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gtk28sbwi"/><path class="hme0rabnh"/><path class="req8k0dco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:graduation-cap" {...props}></Icon>
