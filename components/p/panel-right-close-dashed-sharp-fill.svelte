<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/v0dh77b3j.css';
import '../../css/e/ess6f3oak.css';
import '../../css/q/q_i5o_bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v0dh77b3j"/><path class="ess6f3oak"/><path class="q_i5o_bfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-right-close-dashed-sharp-fill" {...props}></Icon>
