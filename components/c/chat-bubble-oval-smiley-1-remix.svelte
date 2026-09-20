<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nma_pbbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nma_pbbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-oval-smiley-1-remix" {...props}></Icon>
