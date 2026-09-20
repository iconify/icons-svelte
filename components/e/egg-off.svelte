<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru3v4xl0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru3v4xl0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:egg-off" {...props}></Icon>
