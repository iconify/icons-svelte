<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1-rs1b4l.css';
import '../../css/f/fizwjlb_d.css';
import '../../css/f/fs962mxrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="z1-rs1b4l"/><path class="fizwjlb_d"/><path class="fs962mxrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:control-lun-outline-alerted" {...props}></Icon>
