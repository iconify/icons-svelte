<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-6ugubog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p-6ugubog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-cresent-moon-1-night-new-moon-crescent-weather-time-waning" {...props}></Icon>
