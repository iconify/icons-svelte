<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7z-iab4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7z-iab4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-insurance" {...props}></Icon>
