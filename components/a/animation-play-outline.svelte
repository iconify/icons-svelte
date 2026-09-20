<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uevab_bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uevab_bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:animation-play-outline" {...props}></Icon>
