<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eclize6ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="eclize6ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-rain-drop-drops-rain-rainy-meteorology-water-precipitation-weather" {...props}></Icon>
