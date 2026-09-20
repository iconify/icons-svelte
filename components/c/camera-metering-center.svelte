<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kma7s93do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kma7s93do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-metering-center" {...props}></Icon>
