<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1-rs1b4l.css';
import '../../css/s/sga3esc_s.css';
import '../../css/y/y-1brd5iy.css';
import '../../css/l/lmf0ecbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="z1-rs1b4l"/><path class="sga3esc_s"/><path class="y-1brd5iy"/><circle class="lmf0ecbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:control-lun-outline-badged" {...props}></Icon>
