<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/p/pyne1kb6h.css';
import '../../css/u/u3ek8-bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="pyne1kb6h"/><path class="u3ek8-bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-read-bold-duotone" {...props}></Icon>
