<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejx2y1bzf.css';
import '../../css/n/nyjp9ub1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejx2y1bzf"/><path class="nyjp9ub1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-waterdrop-bold-duotone" {...props}></Icon>
