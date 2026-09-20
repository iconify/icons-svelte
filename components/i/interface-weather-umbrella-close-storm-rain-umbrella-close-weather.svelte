<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-oo63zif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g-oo63zif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-umbrella-close-storm-rain-umbrella-close-weather" {...props}></Icon>
