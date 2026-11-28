<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry18-kbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry18-kbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:music-off" {...props}></Icon>
