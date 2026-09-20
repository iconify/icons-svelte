<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rln_3myxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rln_3myxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:crosshair-2-line" {...props}></Icon>
