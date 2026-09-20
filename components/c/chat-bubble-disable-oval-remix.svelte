<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfvhtzbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bfvhtzbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chat-bubble-disable-oval-remix" {...props}></Icon>
