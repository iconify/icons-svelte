<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7x9wfbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g7x9wfbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:lock" {...props}></Icon>
