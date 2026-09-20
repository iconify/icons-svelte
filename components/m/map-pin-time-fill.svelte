<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vts9yxb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vts9yxb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-time-fill" {...props}></Icon>
