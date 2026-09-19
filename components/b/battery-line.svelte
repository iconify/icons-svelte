<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr_-zobgp.css';
import '../../css/p/pj4cy9b9l.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 xr_-zobgp"/><path class="clr-i-outline clr-i-outline-path-2 pj4cy9b9l"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:battery-line" {...props}></Icon>
