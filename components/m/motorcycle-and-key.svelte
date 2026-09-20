<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb6ly69gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jb6ly69gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-and-key" {...props}></Icon>
