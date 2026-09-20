<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir_fjwbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ir_fjwbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:drag-gripper" {...props}></Icon>
