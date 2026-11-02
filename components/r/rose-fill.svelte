<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yue4s31ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yue4s31ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rose-fill" {...props}></Icon>
