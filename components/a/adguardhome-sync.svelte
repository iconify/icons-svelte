<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf4cxs7wl.css';
import '../../css/p/p4ue24b-l.css';
import '../../css/i/ir4rni1pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kf4cxs7wl"/><path class="p4ue24b-l"/><path class="ir4rni1pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adguardhome-sync" {...props}></Icon>
