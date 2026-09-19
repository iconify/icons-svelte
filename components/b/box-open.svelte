<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3t0jgf8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d3t0jgf8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:box-open" {...props}></Icon>
