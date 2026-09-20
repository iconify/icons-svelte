<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzqiss7xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kzqiss7xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-temperature-cold-temperature-thermometer-minus-mercury-cold-weather" {...props}></Icon>
