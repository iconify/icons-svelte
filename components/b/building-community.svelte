<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0dxkwbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0dxkwbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:building-community" {...props}></Icon>
