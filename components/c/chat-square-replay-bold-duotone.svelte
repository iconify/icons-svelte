<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfpn6w7ca.css';
import '../../css/y/yr8y3mtib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfpn6w7ca"/><path class="yr8y3mtib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-replay-bold-duotone" {...props}></Icon>
