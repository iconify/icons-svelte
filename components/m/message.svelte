<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi2vt_c1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi2vt_c1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:message" {...props}></Icon>
