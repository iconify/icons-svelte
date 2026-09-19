<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc49rjbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="dc49rjbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:clip-note-o" {...props}></Icon>
