<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irm4imu1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irm4imu1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-message-outline" {...props}></Icon>
