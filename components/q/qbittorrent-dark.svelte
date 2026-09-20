<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otypypb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="otypypb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qbittorrent-dark" {...props}></Icon>
