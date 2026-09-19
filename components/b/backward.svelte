<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hem6pgwtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hem6pgwtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:backward" {...props}></Icon>
