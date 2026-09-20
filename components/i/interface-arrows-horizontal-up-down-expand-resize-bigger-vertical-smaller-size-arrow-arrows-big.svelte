<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j96f-ebaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j96f-ebaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-horizontal-up-down-expand-resize-bigger-vertical-smaller-size-arrow-arrows-big" {...props}></Icon>
