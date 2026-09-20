<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9o002biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9o002biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qbittorrent-light" {...props}></Icon>
