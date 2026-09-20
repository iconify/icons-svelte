<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caseumbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="caseumbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-cloud-2-cloud-meteorology-cloudy-overcast-cover-weather" {...props}></Icon>
