<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi8ws5jnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi8ws5jnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-off-round" {...props}></Icon>
