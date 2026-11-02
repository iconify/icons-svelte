<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqvdzy66i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqvdzy66i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-3-fill" {...props}></Icon>
