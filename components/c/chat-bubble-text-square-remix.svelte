<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_xjdlbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b_xjdlbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:chat-bubble-text-square-remix" {...props}></Icon>
