<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7txqyfjs.css';
import '../../css/p/px4lcrqbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r7txqyfjs"/><path class="px4lcrqbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pier-20-bold" {...props}></Icon>
