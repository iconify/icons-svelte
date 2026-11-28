<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t19sx_49z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="t19sx_49z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chat-question-thin" {...props}></Icon>
