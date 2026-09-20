<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk0epachj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jk0epachj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-anchor" {...props}></Icon>
