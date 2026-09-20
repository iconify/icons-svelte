<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4pwq5s-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4pwq5s-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-d" {...props}></Icon>
