<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v67rm8qcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v67rm8qcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-smile-ai-3-fill" {...props}></Icon>
