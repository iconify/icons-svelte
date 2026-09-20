<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6k_3kb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u6k_3kb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-horizontal-shrink-resize-shrink-bigger-horizontal-smaller-size-arrow-arrows-big" {...props}></Icon>
