<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc8meib2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc8meib2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chat-bubble-warning" {...props}></Icon>
