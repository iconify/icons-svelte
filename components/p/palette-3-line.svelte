<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chko4obfw.css';
import '../../css/m/m3xop7dba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chko4obfw"/><path class="m3xop7dba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palette-3-line" {...props}></Icon>
