<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qslbzsqwh.css';
import '../../css/t/tg_1r3b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qslbzsqwh"/><path class="tg_1r3b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-bolt-20-bold" {...props}></Icon>
