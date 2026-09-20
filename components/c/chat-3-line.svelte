<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gog8rcokd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gog8rcokd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-3-line" {...props}></Icon>
