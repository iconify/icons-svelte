<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn277tbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn277tbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:deno" {...props}></Icon>
