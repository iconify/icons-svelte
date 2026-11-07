<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k88rdeb7o.css';
import '../../css/u/uy7tz-bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k88rdeb7o"/><path class="uy7tz-bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:armchair-2-bold-duotone" {...props}></Icon>
