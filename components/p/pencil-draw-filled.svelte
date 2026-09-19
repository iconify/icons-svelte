<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mip59zb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mip59zb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pencil-draw-filled" {...props}></Icon>
