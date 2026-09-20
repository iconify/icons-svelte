<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1ileh14j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="d1ileh14j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-temperature-temperature-thermometer-weather-level-meter-mercury-measure" {...props}></Icon>
