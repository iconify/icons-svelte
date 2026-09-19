<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opi5-vb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="opi5-vb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hands-asl-interpreting" {...props}></Icon>
