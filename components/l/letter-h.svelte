<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfxsk6b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfxsk6b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-h" {...props}></Icon>
