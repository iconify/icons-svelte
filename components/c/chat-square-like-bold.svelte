<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp3xxybqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zp3xxybqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-like-bold" {...props}></Icon>
