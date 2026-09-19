<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pue5zmbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pue5zmbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:eraser" {...props}></Icon>
