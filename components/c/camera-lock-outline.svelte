<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4mpn3iau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4mpn3iau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-lock-outline" {...props}></Icon>
