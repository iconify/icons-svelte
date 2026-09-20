<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta3ahwb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta3ahwb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-time-line" {...props}></Icon>
