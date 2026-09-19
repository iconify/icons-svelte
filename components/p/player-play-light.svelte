<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu9si2flt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu9si2flt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-play-light" {...props}></Icon>
