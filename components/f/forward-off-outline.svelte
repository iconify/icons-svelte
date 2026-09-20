<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix1cghcpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix1cghcpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:forward-off-outline" {...props}></Icon>
