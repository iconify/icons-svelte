<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3x_ug_ff.css';
import '../../css/t/tb35ynitm.css';
import '../../css/e/edwd7ibhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3x_ug_ff"/><path class="tb35ynitm"/><path class="edwd7ibhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:record-minimalistic-bold-duotone" {...props}></Icon>
