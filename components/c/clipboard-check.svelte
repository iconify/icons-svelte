<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri3ffybak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ri3ffybak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:clipboard-check" {...props}></Icon>
