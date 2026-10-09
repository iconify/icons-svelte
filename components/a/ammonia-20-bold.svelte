<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p483qmvuq.css';
import '../../css/i/i30_rk_1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p483qmvuq"/><path class="i30_rk_1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammonia-20-bold" {...props}></Icon>
