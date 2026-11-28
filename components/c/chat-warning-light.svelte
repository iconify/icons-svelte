<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln6tvtbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ln6tvtbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chat-warning-light" {...props}></Icon>
