<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwbb8x53o.css';
import '../../css/m/mufw90bzh.css';
import '../../css/p/pvxhf4bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nwbb8x53o"/><path class="mufw90bzh"/><path class="pvxhf4bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:helideck-20-bold" {...props}></Icon>
