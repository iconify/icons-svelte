<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz0ib6bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz0ib6bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-i" {...props}></Icon>
