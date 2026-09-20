<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i04rcb0gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i04rcb0gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:microchip-solid" {...props}></Icon>
