<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmt2g6bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vmt2g6bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pancreas" {...props}></Icon>
