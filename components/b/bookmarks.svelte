<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpk8h1bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpk8h1bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:bookmarks" {...props}></Icon>
