<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di6nw9_ac.css';
import '../../css/p/pzmzhxbns.css';
import '../../css/x/xcd9w1bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="di6nw9_ac"/><path class="pzmzhxbns"/><path class="xcd9w1bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lng-ship-20-bold" {...props}></Icon>
