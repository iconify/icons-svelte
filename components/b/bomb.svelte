<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr5t_bc0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zr5t_bc0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bomb" {...props}></Icon>
