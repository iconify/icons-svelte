<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg73f3bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tg73f3bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-oval-left-ellipsis-solid" {...props}></Icon>
