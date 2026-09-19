<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t21ftq4_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t21ftq4_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-camera-movie" {...props}></Icon>
