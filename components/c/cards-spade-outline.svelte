<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we0x77s-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we0x77s-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-spade-outline" {...props}></Icon>
