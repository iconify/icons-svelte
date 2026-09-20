<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fen0n320y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fen0n320y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cup-off-outline" {...props}></Icon>
