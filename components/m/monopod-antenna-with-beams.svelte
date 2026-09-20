<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-v94cnaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j-v94cnaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:monopod-antenna-with-beams" {...props}></Icon>
