<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djec45b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djec45b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:joystick-sharp" {...props}></Icon>
