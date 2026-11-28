<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccop-1btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ccop-1btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:line-height" {...props}></Icon>
