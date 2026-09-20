<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0seggevd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0seggevd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-image" {...props}></Icon>
