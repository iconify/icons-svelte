<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f2efxzbdp.css';
import '../../css/h/hm5eixlye.css';
import '../../css/h/hgp61kd_e.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="f2efxzbdp"/><path clip-rule="evenodd" class="hm5eixlye"/><path class="hgp61kd_e"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:duplicate-off" {...props}></Icon>
