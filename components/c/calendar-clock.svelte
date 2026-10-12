<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sm_karjot.css';
import '../../css/i/ifivxibrp.css';
import '../../css/r/rmz5vlbcs.css';
import '../../css/s/s328x16br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="sm_karjot"/><rect class="ifivxibrp"/><circle class="rmz5vlbcs"/><path class="s328x16br"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:calendar-clock" {...props}></Icon>
