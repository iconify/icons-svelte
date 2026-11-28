<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl1-wob7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dl1-wob7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-check-bold" {...props}></Icon>
