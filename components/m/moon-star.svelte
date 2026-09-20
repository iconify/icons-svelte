<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzon76bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzon76bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:moon-star" {...props}></Icon>
