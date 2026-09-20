<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkx4vubwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkx4vubwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:computer-camera-off-line" {...props}></Icon>
