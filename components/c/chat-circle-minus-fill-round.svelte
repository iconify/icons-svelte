<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7oac0bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7oac0bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-minus-fill-round" {...props}></Icon>
