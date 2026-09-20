<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f40os-3wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f40os-3wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pin-pad-with-shekel" {...props}></Icon>
