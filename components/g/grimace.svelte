<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0-79bbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j0-79bbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:grimace" {...props}></Icon>
