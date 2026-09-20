<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp2_b80ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp2_b80ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:message-ai-3-fill" {...props}></Icon>
