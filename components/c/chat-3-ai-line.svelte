<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex2o6fw_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex2o6fw_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-3-ai-line" {...props}></Icon>
