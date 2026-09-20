<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g502oxbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g502oxbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:avatar-square-minus" {...props}></Icon>
