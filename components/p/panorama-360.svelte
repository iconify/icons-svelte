<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t515o7b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t515o7b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:panorama-360" {...props}></Icon>
