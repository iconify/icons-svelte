<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl_of99ub.css';
import '../../css/v/vucxpmn0x.css';
import '../../css/e/e2qoovbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tl_of99ub"/><path class="vucxpmn0x"/><path class="e2qoovbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:feed-in-48-bold" {...props}></Icon>
