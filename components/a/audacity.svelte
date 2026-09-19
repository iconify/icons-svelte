<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpnp057-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vpnp057-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:audacity" {...props}></Icon>
