<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk99yguzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk99yguzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-4-ai-line" {...props}></Icon>
