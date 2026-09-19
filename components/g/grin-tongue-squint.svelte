<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1b3pxbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i1b3pxbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:grin-tongue-squint" {...props}></Icon>
