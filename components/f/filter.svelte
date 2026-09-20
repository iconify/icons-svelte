<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0y22ccdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0y22ccdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:filter" {...props}></Icon>
