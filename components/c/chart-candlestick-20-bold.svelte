<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvyc-pbfw.css';
import '../../css/b/bc5q17qnd.css';
import '../../css/t/tnaewda9i.css';
import '../../css/c/coha5wfoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hvyc-pbfw"/><path class="bc5q17qnd"/><path class="tnaewda9i"/><path class="coha5wfoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-candlestick-20-bold" {...props}></Icon>
