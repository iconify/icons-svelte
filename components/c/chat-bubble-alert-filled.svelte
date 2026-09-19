<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7vu07rmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7vu07rmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-bubble-alert-filled" {...props}></Icon>
