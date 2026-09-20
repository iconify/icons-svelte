<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjbg4zucq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cjbg4zucq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-horizontal-expand-expand-resize-bigger-horizontal-smaller-size-arrow-arrows-big" {...props}></Icon>
