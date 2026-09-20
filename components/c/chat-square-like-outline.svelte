<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddldl_4lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddldl_4lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-like-outline" {...props}></Icon>
