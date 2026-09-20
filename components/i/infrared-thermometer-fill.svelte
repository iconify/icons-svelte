<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fab1iab3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fab1iab3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:infrared-thermometer-fill" {...props}></Icon>
