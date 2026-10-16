<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-q-p1bwi.css';
import '../../css/u/u92x8ejul.css';
import '../../css/q/qgl0xjg6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m-q-p1bwi"/><path class="u92x8ejul"/><path class="qgl0xjg6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-x-20-bold" {...props}></Icon>
