<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut8x6ebqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut8x6ebqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:linux" {...props}></Icon>
