<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekoozwbhq.css';
import '../../css/c/csilaps2y.css';
import '../../css/n/nz2-r9bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="ekoozwbhq"/><rect class="csilaps2y"/><path class="nz2-r9bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:hardware-chip-outline" {...props}></Icon>
