<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/r/rd9mw5o4z.css';
import '../../css/e/exgnwabga.css';
import '../../css/h/hcvmaqbuv.css';
import '../../css/i/i46u6tbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><rect class="rd9mw5o4z"/><path class="exgnwabga"/><circle class="hcvmaqbuv"/><path class="i46u6tbey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:camera-three" {...props}></Icon>
