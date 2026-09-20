<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_kyjebew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f_kyjebew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-temperature-hot-temperature-thermometer-hot-mercury-plus-weather" {...props}></Icon>
