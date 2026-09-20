<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv33yzfey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv33yzfey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:bottle-wine" {...props}></Icon>
