<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/x/xitusjssr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="xitusjssr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:branching-paths-down-bold-duotone" {...props}></Icon>
