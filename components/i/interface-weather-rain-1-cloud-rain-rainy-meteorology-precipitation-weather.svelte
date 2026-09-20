<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm9um7bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tm9um7bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-rain-1-cloud-rain-rainy-meteorology-precipitation-weather" {...props}></Icon>
