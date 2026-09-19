<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akv7glb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akv7glb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-microchip" {...props}></Icon>
