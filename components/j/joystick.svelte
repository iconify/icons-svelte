<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iub7stbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iub7stbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:joystick" {...props}></Icon>
