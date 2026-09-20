<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no--e8__i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="no--e8__i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:desktop-chat-solid" {...props}></Icon>
