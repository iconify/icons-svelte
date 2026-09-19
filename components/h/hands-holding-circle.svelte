<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g90kx7ply.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g90kx7ply"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hands-holding-circle" {...props}></Icon>
