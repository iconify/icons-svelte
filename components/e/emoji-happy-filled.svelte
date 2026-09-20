<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqga1ycio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqga1ycio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:emoji-happy-filled" {...props}></Icon>
