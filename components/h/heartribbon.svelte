<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwsggl4nt.css';
import '../../css/w/w2kpx3bru.css';
import '../../css/b/bajemy94v.css';
import '../../css/v/vfdxbdcpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwsggl4nt"/><path class="w2kpx3bru"/><path class="bajemy94v"/><path class="vfdxbdcpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heartribbon" {...props}></Icon>
