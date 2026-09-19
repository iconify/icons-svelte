<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxlk60b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="gxlk60b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:clip-note" {...props}></Icon>
