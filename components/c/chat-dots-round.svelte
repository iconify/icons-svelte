<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h09mocyzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h09mocyzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-dots-round" {...props}></Icon>
