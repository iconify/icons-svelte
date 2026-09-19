<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt7cz-bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt7cz-bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:arc-browser" {...props}></Icon>
