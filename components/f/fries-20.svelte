<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qot8k_bnm.css';
import '../../css/u/uivgpybzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qot8k_bnm"/><path class="uivgpybzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fries-20" {...props}></Icon>
