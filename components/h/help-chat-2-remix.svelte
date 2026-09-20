<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0yh1rdxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r0yh1rdxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:help-chat-2-remix" {...props}></Icon>
