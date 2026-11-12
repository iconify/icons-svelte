<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlgv7ybbq.css';
import '../../css/b/bpn70zs4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wlgv7ybbq"/><path class="bpn70zs4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rackula" {...props}></Icon>
