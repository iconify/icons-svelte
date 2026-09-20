<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbkvt_4lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbkvt_4lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-voice-off" {...props}></Icon>
