<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8cq6cc5u.css';
import '../../css/m/mjdmcab3w.css';
import '../../css/t/tq7go-bpr.css';
import '../../css/d/dld29ukqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8cq6cc5u"/><path class="mjdmcab3w"/><path class="tq7go-bpr"/><path class="dld29ukqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:point-on-map-perspective-bold" {...props}></Icon>
