<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di5-yddwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di5-yddwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-heart-fill" {...props}></Icon>
