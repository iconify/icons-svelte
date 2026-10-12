<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9emokusn.css';
import '../../css/m/mpu2txpdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m9emokusn"/><path class="mpu2txpdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cow-48-bold" {...props}></Icon>
