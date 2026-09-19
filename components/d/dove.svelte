<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1wm25bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j1wm25bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:dove" {...props}></Icon>
