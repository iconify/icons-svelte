<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vh_hv9bgh.css';
import '../../css/t/tf2_hbigc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vh_hv9bgh"/><path class="tf2_hbigc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:bold-duotone" {...props}></Icon>
