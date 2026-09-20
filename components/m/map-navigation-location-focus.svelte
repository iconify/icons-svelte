<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7ioqnsvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a7ioqnsvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:map-navigation-location-focus" {...props}></Icon>
