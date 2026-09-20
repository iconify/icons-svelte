<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p2vd3xbgk.css';
import '../../css/j/j3gpqnbek.css';
import '../../css/m/mmdgk3bof.css';
import '../../css/u/u1i3dbl4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p2vd3xbgk"/><path class="j3gpqnbek"/><path class="mmdgk3bof"/><path class="u1i3dbl4x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:cloud-down-off" {...props}></Icon>
