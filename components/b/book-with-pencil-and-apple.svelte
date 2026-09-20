<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa33cw15g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pa33cw15g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-pencil-and-apple" {...props}></Icon>
