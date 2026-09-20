<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds5-kubap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ds5-kubap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-windmill-windmill-velocity-weather-wind" {...props}></Icon>
