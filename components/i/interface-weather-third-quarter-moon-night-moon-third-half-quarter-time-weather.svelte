<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ody3_jmli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ody3_jmli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-third-quarter-moon-night-moon-third-half-quarter-time-weather" {...props}></Icon>
