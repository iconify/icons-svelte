<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzi-d4bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzi-d4bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-police" {...props}></Icon>
