<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf4cxs7wl.css';
import '../../css/p/p4ue24b-l.css';
import '../../css/g/g_8ei9bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kf4cxs7wl"/><path class="p4ue24b-l"/><path class="g_8ei9bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adguardhome-sync" {...props}></Icon>
