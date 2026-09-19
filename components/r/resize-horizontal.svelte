<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c34mxabax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="c34mxabax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:resize-horizontal" {...props}></Icon>
