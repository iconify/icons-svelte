<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y653e0pli.css';
import '../../css/y/yol3kp1rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="y653e0pli"/><path class="yol3kp1rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:releasewatcher" {...props}></Icon>
