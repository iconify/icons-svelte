<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns6fbwp0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ns6fbwp0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-sun-1-cloud-meteorology-cloudy-partly-sunny-weather" {...props}></Icon>
