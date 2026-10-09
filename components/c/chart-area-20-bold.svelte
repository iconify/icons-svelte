<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aezfh675b.css';
import '../../css/x/x-kkv_b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aezfh675b"/><path class="x-kkv_b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-area-20-bold" {...props}></Icon>
