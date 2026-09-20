<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0cq1fbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0cq1fbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mouse-move-down" {...props}></Icon>
