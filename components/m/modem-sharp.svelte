<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cecxa5ukj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cecxa5ukj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:modem-sharp" {...props}></Icon>
