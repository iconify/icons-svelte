<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agsf1c4-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agsf1c4-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eraser-fill" {...props}></Icon>
