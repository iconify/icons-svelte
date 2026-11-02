<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyq324bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyq324bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mcp-line" {...props}></Icon>
