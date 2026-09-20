<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2d7aoyzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j2d7aoyzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:note-16" {...props}></Icon>
