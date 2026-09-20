<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv-m53agm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hv-m53agm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:chat-bubble-typing-oval-remix" {...props}></Icon>
