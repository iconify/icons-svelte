<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9045w0jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i9045w0jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sleeping-in-bed-between-floor-and-ceiling" {...props}></Icon>
