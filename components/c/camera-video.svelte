<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/oyei4sb8x.css';
import '../../css/p/pb2cbbcpz.css';
import '../../css/z/z1jh5abfk.css';
import '../../css/i/i_vfs1szn.css';
import '../../css/f/fpn5tub8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="oyei4sb8x"/><path class="pb2cbbcpz"/><path class="z1jh5abfk"/><circle class="i_vfs1szn"/><circle class="fpn5tub8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:camera-video" {...props}></Icon>
