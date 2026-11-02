<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2ft0mbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2ft0mbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-1-ai-fill" {...props}></Icon>
