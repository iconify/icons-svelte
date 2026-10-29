<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pvtarpb7m.css';
import '../../css/s/sukohubkj.css';
import '../../css/w/wa7muobyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pvtarpb7m"/><path class="sukohubkj wm-a"/><path class="wa7muobyt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-bar-duo" {...props}></Icon>
