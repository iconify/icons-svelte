<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sm_karjot.css';
import '../../css/m/m1iho-bvd.css';
import '../../css/r/rmz5vlbcs.css';
import '../../css/x/xflnghb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="sm_karjot"/><path class="m1iho-bvd"/><circle class="rmz5vlbcs"/><path class="xflnghb0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:calendar-clock" {...props}></Icon>
