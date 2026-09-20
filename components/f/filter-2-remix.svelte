<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrqen7b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lrqen7b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:filter-2-remix" {...props}></Icon>
