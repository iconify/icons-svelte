<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czxf_zkwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czxf_zkwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-oval-left-ellipsis" {...props}></Icon>
