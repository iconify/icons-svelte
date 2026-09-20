<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln56x6-6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ln56x6-6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-oval-smiley-1-solid" {...props}></Icon>
