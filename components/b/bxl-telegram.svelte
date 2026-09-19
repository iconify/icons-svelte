<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur14avi_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur14avi_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-telegram" {...props}></Icon>
