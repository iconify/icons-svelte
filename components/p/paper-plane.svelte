<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5pdp9b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j5pdp9b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:paper-plane" {...props}></Icon>
