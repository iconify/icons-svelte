<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv8psl0zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cv8psl0zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-square-warning-remix" {...props}></Icon>
