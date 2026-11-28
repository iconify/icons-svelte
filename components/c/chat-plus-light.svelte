<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saeiwpb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="saeiwpb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chat-plus-light" {...props}></Icon>
