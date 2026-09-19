<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m74_d7bth.css';
import '../../css/k/ky4ks4bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m74_d7bth"/><path class="ky4ks4bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:filter-square" {...props}></Icon>
