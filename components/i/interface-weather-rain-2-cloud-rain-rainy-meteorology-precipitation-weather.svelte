<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1nckkbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c1nckkbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-rain-2-cloud-rain-rainy-meteorology-precipitation-weather" {...props}></Icon>
