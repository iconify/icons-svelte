<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u43xfbckx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u43xfbckx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-left-ellipsis-20-solid" {...props}></Icon>
