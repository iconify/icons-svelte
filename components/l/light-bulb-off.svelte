<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubh0g-bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubh0g-bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:light-bulb-off" {...props}></Icon>
