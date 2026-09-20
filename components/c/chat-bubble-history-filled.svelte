<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pak4c7bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pak4c7bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-bubble-history-filled" {...props}></Icon>
