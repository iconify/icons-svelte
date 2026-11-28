<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf4c73b8m.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mg0ugob5a.css';
import '../../css/g/gcq-pnbnm.css';
import '../../css/m/mebfxw_io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yf4c73b8m"/><g class="dt0cm9dhy primary"><path class="mg0ugob5a"/><path class="gcq-pnbnm"/><path class="mebfxw_io"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lamp-ceiling-duo" {...props}></Icon>
