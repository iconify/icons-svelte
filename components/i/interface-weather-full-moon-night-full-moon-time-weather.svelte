<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0tuhogfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<circle class="i0tuhogfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-weather-full-moon-night-full-moon-time-weather" {...props}></Icon>
