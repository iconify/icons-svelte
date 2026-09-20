<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0aegk_3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0aegk_3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-plus" {...props}></Icon>
