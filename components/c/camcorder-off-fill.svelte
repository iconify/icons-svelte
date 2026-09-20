<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co2uwj05c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co2uwj05c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-off-fill" {...props}></Icon>
