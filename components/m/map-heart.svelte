<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipwm09bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipwm09bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-heart" {...props}></Icon>
