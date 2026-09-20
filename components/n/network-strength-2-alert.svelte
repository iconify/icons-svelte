<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrumi43vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrumi43vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-strength-2-alert" {...props}></Icon>
