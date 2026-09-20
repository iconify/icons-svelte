<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtsm27bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vtsm27bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:chat-bubble-oval-smiley-1-remix" {...props}></Icon>
