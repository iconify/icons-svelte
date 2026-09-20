<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk9j0tbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jk9j0tbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:milk-carton-and-apple-and-shekel" {...props}></Icon>
