<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/eym7bl_re.css';
import '../../css/t/tay61hbyz.css';
import '../../css/f/f4vx4ccga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eym7bl_re"/><path class="tay61hbyz"/><path class="f4vx4ccga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:monitor-off-sharp-duotone" {...props}></Icon>
