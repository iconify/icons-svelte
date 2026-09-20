<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdclnynbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wdclnynbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chat-bubble-square-block-remix" {...props}></Icon>
