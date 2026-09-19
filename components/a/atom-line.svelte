<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifii5lbxf.css';
import '../../css/v/voor-mbwk.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ifii5lbxf"/><path class="clr-i-outline clr-i-outline-path-2 voor-mbwk"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:atom-line" {...props}></Icon>
