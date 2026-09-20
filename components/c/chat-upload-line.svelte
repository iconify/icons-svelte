<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riqks3bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="riqks3bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-upload-line" {...props}></Icon>
