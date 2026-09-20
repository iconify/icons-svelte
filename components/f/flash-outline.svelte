<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw9-8sbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw9-8sbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:flash-outline" {...props}></Icon>
