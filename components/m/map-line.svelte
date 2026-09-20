<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmt21rbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmt21rbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-line" {...props}></Icon>
