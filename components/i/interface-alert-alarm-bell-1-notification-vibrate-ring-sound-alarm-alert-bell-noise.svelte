<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c83vv2bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c83vv2bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-alert-alarm-bell-1-notification-vibrate-ring-sound-alarm-alert-bell-noise" {...props}></Icon>
