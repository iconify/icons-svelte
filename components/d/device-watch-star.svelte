<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aedn4qbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aedn4qbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-star" {...props}></Icon>
