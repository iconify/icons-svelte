<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybzc4rbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybzc4rbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:library" {...props}></Icon>
