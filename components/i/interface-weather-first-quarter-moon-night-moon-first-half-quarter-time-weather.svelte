<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vym98jbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vym98jbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-first-quarter-moon-night-moon-first-half-quarter-time-weather" {...props}></Icon>
