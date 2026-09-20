<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1rz5ob3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y1rz5ob3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:paint" {...props}></Icon>
