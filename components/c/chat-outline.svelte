<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndlt7bcrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndlt7bcrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-outline" {...props}></Icon>
