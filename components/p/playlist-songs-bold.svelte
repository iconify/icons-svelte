<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2ub02obh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2ub02obh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:playlist-songs-bold" {...props}></Icon>
