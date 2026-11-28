<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvuzmly5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="kvuzmly5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:line-height-bold" {...props}></Icon>
