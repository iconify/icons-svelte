<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc5mk5wwa.css';
import '../../css/c/csdxkcclh.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc5mk5wwa"/><path class="csdxkcclh"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-video-camera-filled" {...props}></Icon>
