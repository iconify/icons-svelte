<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkt_eriht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkt_eriht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:openwrt-logo" {...props}></Icon>
