<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jddywnb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jddywnb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chat-question-bold" {...props}></Icon>
