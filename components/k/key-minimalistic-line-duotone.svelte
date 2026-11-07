<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fvm71nh3d.css';
import '../../css/t/tmpf65c9n.css';
import '../../css/c/ckcnl295s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fvm71nh3d"/><path class="tmpf65c9n"/><path class="ckcnl295s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-line-duotone" {...props}></Icon>
