<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq5sj8rvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq5sj8rvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:colors-swatch" {...props}></Icon>
