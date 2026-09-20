<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b315-1bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b315-1bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:image-flash" {...props}></Icon>
