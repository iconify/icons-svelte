<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2r4zdngh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2r4zdngh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:estate-sharp" {...props}></Icon>
