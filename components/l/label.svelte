<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luio64b5z.css';
import '../../css/j/j6ei9utzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="luio64b5z"/><path class="j6ei9utzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:label" {...props}></Icon>
