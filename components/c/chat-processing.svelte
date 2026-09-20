<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcf3lkbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcf3lkbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-processing" {...props}></Icon>
