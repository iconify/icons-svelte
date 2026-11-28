<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d_plodt-s.css';
import '../../css/o/oi3kjkbsp.css';
import '../../css/f/ffxep2b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d_plodt-s"/><path class="oi3kjkbsp"/><path class="ffxep2b5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-search" {...props}></Icon>
