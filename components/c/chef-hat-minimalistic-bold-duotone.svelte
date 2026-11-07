<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zscshfblg.css';
import '../../css/f/fpavm-beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zscshfblg"/><path class="fpavm-beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chef-hat-minimalistic-bold-duotone" {...props}></Icon>
