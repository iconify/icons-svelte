<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-wa5cb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r-wa5cb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:graph-arrow-increase-remix" {...props}></Icon>
