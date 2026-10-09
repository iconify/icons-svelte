<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_-7pbckv.css';
import '../../css/p/p39fyrbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r_-7pbckv"/><path class="p39fyrbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:draught-proofing-48-bold" {...props}></Icon>
