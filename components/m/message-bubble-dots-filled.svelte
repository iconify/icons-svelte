<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piykylb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piykylb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-dots-filled" {...props}></Icon>
