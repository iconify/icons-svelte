<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/s/s4s7nircm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="s4s7nircm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:compass-square-bold-duotone" {...props}></Icon>
