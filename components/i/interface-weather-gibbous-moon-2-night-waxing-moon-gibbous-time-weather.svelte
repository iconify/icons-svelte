<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khluvqi-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="khluvqi-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-gibbous-moon-2-night-waxing-moon-gibbous-time-weather" {...props}></Icon>
