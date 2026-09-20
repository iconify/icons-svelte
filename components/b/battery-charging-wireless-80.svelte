<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbs_lyb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbs_lyb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-wireless-80" {...props}></Icon>
