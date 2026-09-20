<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgn9s7blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgn9s7blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chart-minus" {...props}></Icon>
