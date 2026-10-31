<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzag8xbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzag8xbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-plus-fill-round" {...props}></Icon>
