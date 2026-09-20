<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epib1doug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epib1doug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:book" {...props}></Icon>
