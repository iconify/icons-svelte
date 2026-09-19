<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onyqr8g1f.css';
import '../../css/a/a5ljf0bmb.css';
import '../../css/h/hcj7zv6_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="onyqr8g1f"/><path class="a5ljf0bmb"/><path class="hcj7zv6_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:bg-1x1" {...props}></Icon>
