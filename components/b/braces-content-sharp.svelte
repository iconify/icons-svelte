<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1y6j3b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1y6j3b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:braces-content-sharp" {...props}></Icon>
