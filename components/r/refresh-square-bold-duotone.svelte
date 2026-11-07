<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn_frcb-c.css';
import '../../css/g/gcj62obsa.css';
import '../../css/f/fwihx0b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_frcb-c"/><path class="gcj62obsa"/><path class="fwihx0b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:refresh-square-bold-duotone" {...props}></Icon>
