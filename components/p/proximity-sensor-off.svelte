<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmh25jbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmh25jbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:proximity-sensor-off" {...props}></Icon>
