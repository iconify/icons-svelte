<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2aouwtou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2aouwtou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mouse-left-click-outline" {...props}></Icon>
