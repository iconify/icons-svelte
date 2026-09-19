<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xteprklyo.css';
import '../../css/m/moem5k2vk.css';
import '../../css/z/zy870cbtg.css';
import '../../css/a/al9qvobnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xteprklyo"/><path class="moem5k2vk"/><circle class="zy870cbtg"/><ellipse class="al9qvobnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mv-1x1" {...props}></Icon>
