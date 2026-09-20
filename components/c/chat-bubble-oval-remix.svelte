<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujq65ebsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ujq65ebsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-oval-remix" {...props}></Icon>
