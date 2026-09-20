<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d62az0bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d62az0bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-controller-off" {...props}></Icon>
