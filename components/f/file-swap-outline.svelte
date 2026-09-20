<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyng10oup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyng10oup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-swap-outline" {...props}></Icon>
