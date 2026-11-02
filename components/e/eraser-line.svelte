<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl98cu6fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl98cu6fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eraser-line" {...props}></Icon>
