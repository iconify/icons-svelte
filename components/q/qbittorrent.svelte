<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em1x7dc1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em1x7dc1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:qbittorrent" {...props}></Icon>
