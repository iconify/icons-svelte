<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncjcrccsd.css';
import '../../css/w/wfyvh_b2x.css';
import '../../css/r/r5bqwybgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ncjcrccsd"/><path class="wfyvh_b2x"/><path class="r5bqwybgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:luggage-20-bold" {...props}></Icon>
