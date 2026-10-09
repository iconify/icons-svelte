<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxzl1bc0g.css';
import '../../css/e/e6or4bcld.css';
import '../../css/a/a2_nmqdnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xxzl1bc0g"/><path class="e6or4bcld"/><path class="a2_nmqdnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camper-van-20-bold" {...props}></Icon>
