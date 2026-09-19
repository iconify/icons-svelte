<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tif8-1b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tif8-1b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:http" {...props}></Icon>
