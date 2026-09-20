<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjs1y2sgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjs1y2sgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:remixicon-fill" {...props}></Icon>
