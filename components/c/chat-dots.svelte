<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0_ubqbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0_ubqbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chat-dots" {...props}></Icon>
