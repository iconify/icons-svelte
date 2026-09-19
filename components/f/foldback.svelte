<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1zlwfbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i1zlwfbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:foldback" {...props}></Icon>
