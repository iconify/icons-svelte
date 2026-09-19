<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j042-s57z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j042-s57z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chat-sparkle-error" {...props}></Icon>
