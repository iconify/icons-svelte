<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vgcmxccix.css';
import '../../css/x/xlramcbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":32};
const content = `<g class="cuyn6tgcc"><path class="vgcmxccix"/><path class="xlramcbzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:alarmclock" {...props}></Icon>
