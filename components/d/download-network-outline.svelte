<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy2tmbbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy2tmbbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:download-network-outline" {...props}></Icon>
