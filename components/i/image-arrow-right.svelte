<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxg1m2b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxg1m2b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:image-arrow-right" {...props}></Icon>
