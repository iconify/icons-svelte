<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9k425tao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9k425tao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:images" {...props}></Icon>
