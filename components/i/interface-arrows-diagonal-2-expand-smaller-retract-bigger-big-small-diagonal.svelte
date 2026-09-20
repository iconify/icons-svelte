<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifutwnbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ifutwnbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-diagonal-2-expand-smaller-retract-bigger-big-small-diagonal" {...props}></Icon>
