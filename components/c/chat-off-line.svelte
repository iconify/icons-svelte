<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzkzmbc4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzkzmbc4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-off-line" {...props}></Icon>
