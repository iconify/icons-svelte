<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfyhsib7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfyhsib7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:camera-face" {...props}></Icon>
