<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt3m2bate.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt3m2bate"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-check-round" {...props}></Icon>
