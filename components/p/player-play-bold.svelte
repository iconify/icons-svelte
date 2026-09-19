<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp8cawbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp8cawbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-play-bold" {...props}></Icon>
