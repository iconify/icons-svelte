<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvbcrablp.css';
import '../../css/l/lwrg85til.css';
import '../../css/v/vcu04ebhz.css';
import '../../css/i/iysev6bne.css';
import '../../css/d/dxnrye12r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvbcrablp"/><path class="lwrg85til"/><path class="vcu04ebhz"/><path class="iysev6bne"/><path class="dxnrye12r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bot-bold-duotone" {...props}></Icon>
