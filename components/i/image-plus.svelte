<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eerj2nbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eerj2nbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:image-plus" {...props}></Icon>
