<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e81d7qbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e81d7qbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:milk-carton-and-apple-and-rupee" {...props}></Icon>
