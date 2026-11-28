<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1tq014el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u1tq014el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chat-question-light" {...props}></Icon>
