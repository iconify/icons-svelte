<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv84ipf1b.css';
import '../../css/s/s2eur9scr.css';
import '../../css/e/eu4khzs_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zv84ipf1b"/><path class="s2eur9scr"/><path class="eu4khzs_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:houseboat-20" {...props}></Icon>
