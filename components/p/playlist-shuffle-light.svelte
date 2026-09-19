<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxqrty3pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxqrty3pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:playlist-shuffle-light" {...props}></Icon>
