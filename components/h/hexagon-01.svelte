<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz-k7ho-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-k7ho-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hexagon-01" {...props}></Icon>
