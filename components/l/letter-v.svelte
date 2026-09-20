<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydj0vvb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydj0vvb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-v" {...props}></Icon>
