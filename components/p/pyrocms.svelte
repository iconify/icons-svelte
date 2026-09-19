<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j01bfxbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":642,"height":1025};
const content = `<path class="j01bfxbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pyrocms" {...props}></Icon>
