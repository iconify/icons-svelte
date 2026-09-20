<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8e5vfbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8e5vfbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:debug-stop" {...props}></Icon>
