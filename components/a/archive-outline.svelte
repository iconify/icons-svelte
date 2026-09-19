<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5d2dxbxx.css';
import '../../css/p/ppcl3rr7n.css';
import '../../css/l/lxd_jw--n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s5d2dxbxx"/><rect class="ppcl3rr7n"/><path class="lxd_jw--n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:archive-outline" {...props}></Icon>
