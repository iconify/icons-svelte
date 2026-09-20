<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w35k3sp7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w35k3sp7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-oval-smiley-2-remix" {...props}></Icon>
