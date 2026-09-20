<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz6ef4bsh.css';
import '../../css/u/uqdpf65ef.css';
import '../../css/j/jf5jiy4cv.css';
import '../../css/t/tpdj2bgpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wz6ef4bsh"/><circle class="uqdpf65ef"/><path class="jf5jiy4cv"/><path class="tpdj2bgpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cannoli-shell" {...props}></Icon>
