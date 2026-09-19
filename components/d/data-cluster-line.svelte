<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd0bncbmo.css';
import '../../css/z/zcfdmshpr.css';
import '../../css/y/yon6j8aod.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 kd0bncbmo"/><path class="clr-i-outline clr-i-outline-path-2 zcfdmshpr"/><path class="clr-i-outline clr-i-outline-path-3 yon6j8aod"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:data-cluster-line" {...props}></Icon>
