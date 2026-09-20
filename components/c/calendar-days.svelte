<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w_c3gfbrx.css';
import '../../css/o/ok8e9k-vg.css';
import '../../css/w/w7r1_zifi.css';
import '../../css/r/rqb69engq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w_c3gfbrx"/><rect class="ok8e9k-vg"/><path class="w7r1_zifi"/><path class="rqb69engq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-days" {...props}></Icon>
