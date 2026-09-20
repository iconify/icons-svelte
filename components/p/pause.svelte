<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qze7ds5pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qze7ds5pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pause" {...props}></Icon>
