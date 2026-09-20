<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1blm2b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1blm2b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:bluetooth" {...props}></Icon>
