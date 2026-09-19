<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws3dbbcgn.css';
import '../../css/p/p1ijl2b0l.css';
import '../../css/y/yo8uw-b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ws3dbbcgn"/><path class="p1ijl2b0l"/><circle class="yo8uw-b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:flower-outline" {...props}></Icon>
