<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/q/qbaf_kc0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="qbaf_kc0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fire-square-bold-duotone" {...props}></Icon>
