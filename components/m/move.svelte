<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk4ocrbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk4ocrbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:move" {...props}></Icon>
