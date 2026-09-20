<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgdfcyd0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgdfcyd0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-spade-outline" {...props}></Icon>
