<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clluj0x1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clluj0x1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-1-fill" {...props}></Icon>
