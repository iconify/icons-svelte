<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr3dwwbcg.css';
import '../../css/k/ki68ofbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr3dwwbcg"/><path class="ki68ofbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filter-close-bold-duotone" {...props}></Icon>
