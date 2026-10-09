<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0oa-qzdz.css';
import '../../css/i/ir9wdpb0n.css';
import '../../css/x/xonacibwr.css';
import '../../css/j/ja9-u5bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="ir9wdpb0n"/><path class="xonacibwr"/><path class="ja9-u5bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:barometer-20-bold" {...props}></Icon>
