<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f77xy6wps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f77xy6wps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-square-write-remix" {...props}></Icon>
