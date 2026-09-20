<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr6lp2beq.css';
import '../../css/m/m74onmbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zr6lp2beq"/><path class="m74onmbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phpsysinfo-light" {...props}></Icon>
