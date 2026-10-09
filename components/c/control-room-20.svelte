<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n56u5w1us.css';
import '../../css/c/cwy5dxbgm.css';
import '../../css/k/kmuwojfof.css';
import '../../css/t/tli3q6bmx.css';
import '../../css/n/n6t65ilhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n56u5w1us"/><path class="cwy5dxbgm"/><path class="kmuwojfof"/><path class="tli3q6bmx"/><path class="n6t65ilhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:control-room-20" {...props}></Icon>
