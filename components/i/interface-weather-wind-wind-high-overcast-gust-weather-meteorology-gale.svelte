<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejcxksb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ejcxksb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-wind-wind-high-overcast-gust-weather-meteorology-gale" {...props}></Icon>
