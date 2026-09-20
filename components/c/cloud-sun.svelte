<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywl8jmbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywl8jmbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cloud-sun" {...props}></Icon>
