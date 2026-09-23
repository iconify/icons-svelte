<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/evxcoq2mj.css';
import '../../css/d/dmrlztban.css';
import '../../css/w/w72_i4b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="evxcoq2mj"/><path class="dmrlztban"/><path class="w72_i4b_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:activity-sparkles-sharp-two-tone" {...props}></Icon>
