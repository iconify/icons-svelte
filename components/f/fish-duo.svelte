<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nh0u_v32h.css';
import '../../css/f/fm32n2byj.css';
import '../../css/b/bq6kxj32x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nh0u_v32h"/><path class="fm32n2byj wm-a"/><path class="bq6kxj32x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fish-duo" {...props}></Icon>
