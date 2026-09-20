<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz__0t3bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz__0t3bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-text-sharp" {...props}></Icon>
