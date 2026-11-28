<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxx0n92ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uxx0n92ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-clock-thin" {...props}></Icon>
