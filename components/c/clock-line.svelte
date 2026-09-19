<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5rcylbor.css';
import '../../css/a/ag725s3cq.css';
import '../../css/h/hv2hqr_7z.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 l5rcylbor"/><path class="ag725s3cq clr-i-outline clr-i-outline-path-2"/><path class="clr-i-outline clr-i-outline-path-3 hv2hqr_7z"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:clock-line" {...props}></Icon>
