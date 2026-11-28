<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvtwf7mtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvtwf7mtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bookmark-off" {...props}></Icon>
