<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzsdd8o_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yzsdd8o_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:paint-roller" {...props}></Icon>
