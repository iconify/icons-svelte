<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcj9e0oij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pcj9e0oij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hands-holding" {...props}></Icon>
