<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rra3jebig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rra3jebig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:drag-and-drop-sharp" {...props}></Icon>
