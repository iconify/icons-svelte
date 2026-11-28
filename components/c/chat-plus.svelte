<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xihhgf-iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xihhgf-iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chat-plus" {...props}></Icon>
