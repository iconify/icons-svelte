<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/netb8tell.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="netb8tell"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mosque-outline" {...props}></Icon>
