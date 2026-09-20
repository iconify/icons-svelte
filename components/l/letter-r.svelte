<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh62xlrrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh62xlrrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-r" {...props}></Icon>
