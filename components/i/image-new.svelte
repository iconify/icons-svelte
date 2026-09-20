<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vamt_-b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vamt_-b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:image-new" {...props}></Icon>
