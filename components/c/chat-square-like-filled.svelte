<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu6dr2k5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu6dr2k5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-square-like-filled" {...props}></Icon>
