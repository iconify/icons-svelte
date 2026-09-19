<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd7tvtbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd7tvtbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-heart-filled" {...props}></Icon>
