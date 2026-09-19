<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnvh5fb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gnvh5fb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:comment-slash" {...props}></Icon>
