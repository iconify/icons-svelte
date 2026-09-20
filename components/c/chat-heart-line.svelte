<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq2f81b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq2f81b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-heart-line" {...props}></Icon>
