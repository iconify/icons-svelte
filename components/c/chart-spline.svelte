<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/z/zh6imhb-f.css';
import '../../css/f/fbk8z1bnm.css';
import '../../css/r/rsyvdzbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow zh6imhb-f"/><path class="fbk8z1bnm wm-shadow"/><path class="rsyvdzbgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:chart-spline" {...props}></Icon>
