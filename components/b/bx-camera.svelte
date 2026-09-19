<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkftr6bal.css';
import '../../css/o/of7e8kpvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkftr6bal"/><path class="of7e8kpvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-camera" {...props}></Icon>
