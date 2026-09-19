<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp7kilijg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp7kilijg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-voice-generator" {...props}></Icon>
