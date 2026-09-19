<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-yawdb2x.css';
import '../../css/j/j5cb_7bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-yawdb2x"/><path class="j5cb_7bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:battery-alert" {...props}></Icon>
