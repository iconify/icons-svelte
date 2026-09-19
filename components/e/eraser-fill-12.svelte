<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjsfgvb4f.css';
import '../../css/u/unp6d04od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zjsfgvb4f"/><path class="unp6d04od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eraser-fill-12" {...props}></Icon>
