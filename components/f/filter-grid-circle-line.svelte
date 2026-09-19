<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5e94ub8h.css';
import '../../css/l/l5rcylbor.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 u5e94ub8h"/><path class="clr-i-outline clr-i-outline-path-2 l5rcylbor"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:filter-grid-circle-line" {...props}></Icon>
