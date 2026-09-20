<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa1e5mbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sa1e5mbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openwrt-light" {...props}></Icon>
