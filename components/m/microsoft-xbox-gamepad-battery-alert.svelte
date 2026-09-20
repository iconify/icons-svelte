<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0vvwhbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0vvwhbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-xbox-gamepad-battery-alert" {...props}></Icon>
