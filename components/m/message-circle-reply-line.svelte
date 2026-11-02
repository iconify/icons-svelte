<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0tt3lbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0tt3lbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-reply-line" {...props}></Icon>
