<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_a8zsbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_a8zsbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-check-fill-round" {...props}></Icon>
