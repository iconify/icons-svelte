<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv9d3tbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rv9d3tbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-gibbous-moon-1-night-moon-weather-gibbous-time-waning" {...props}></Icon>
