<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rujow35iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rujow35iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:monitor-lock" {...props}></Icon>
