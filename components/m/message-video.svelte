<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbwcpk9oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbwcpk9oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:message-video" {...props}></Icon>
