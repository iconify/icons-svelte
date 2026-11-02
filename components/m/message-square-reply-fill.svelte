<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2pim1bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2pim1bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-reply-fill" {...props}></Icon>
