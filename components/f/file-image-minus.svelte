<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry8x41zgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry8x41zgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-image-minus" {...props}></Icon>
