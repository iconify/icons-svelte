<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltt_btmrh.css';
import '../../css/z/zjsm6-byf.css';
import '../../css/b/bxl44g1ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ltt_btmrh"/><path class="zjsm6-byf"/><path class="bxl44g1ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gavel-20" {...props}></Icon>
