<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt-chjbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tt-chjbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-cresent-moon-2-night-new-moon-crescent-waxing-time-weather" {...props}></Icon>
