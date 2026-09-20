<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmob1ccvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmob1ccvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:horoscope-gemini" {...props}></Icon>
