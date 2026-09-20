<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvzdmtb_q.css';
import '../../css/q/q1gzscbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="wvzdmtb_q"/><path class="q1gzscbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:book" {...props}></Icon>
