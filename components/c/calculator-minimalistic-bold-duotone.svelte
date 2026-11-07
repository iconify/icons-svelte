<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/n/n-5gl4b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path clip-rule="evenodd" class="n-5gl4b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calculator-minimalistic-bold-duotone" {...props}></Icon>
