<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipjfvdb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipjfvdb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-3-ai-line" {...props}></Icon>
