<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipvyb0bgr.css';
import '../../css/t/tpa8hn3iv.css';
import '../../css/t/t4lw4kbrl.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ipvyb0bgr"/><path class="clr-i-outline clr-i-outline-path-2 tpa8hn3iv"/><path class="clr-i-outline clr-i-outline-path-3 t4lw4kbrl"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:expand-card-line" {...props}></Icon>
