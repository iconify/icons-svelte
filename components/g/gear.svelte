<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecdxl0m7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecdxl0m7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:gear" {...props}></Icon>
