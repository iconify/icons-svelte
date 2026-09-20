<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiq7_wb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oiq7_wb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-expand-window-1-remix" {...props}></Icon>
