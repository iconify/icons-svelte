<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d96z9pegl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":456};
const content = `<path class="d96z9pegl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:pin-assistant" {...props}></Icon>
