<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdcz7gq1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdcz7gq1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-dots-fill-round" {...props}></Icon>
