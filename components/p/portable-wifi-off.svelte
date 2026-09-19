<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjf1anbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":424};
const content = `<path class="kjf1anbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:portable-wifi-off" {...props}></Icon>
