<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i_j-gqblx.css';
import '../../css/o/ox3ezrunz.css';
import '../../css/w/wa65fi0wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="i_j-gqblx"/><path clip-rule="evenodd" class="ox3ezrunz"/><path class="wa65fi0wq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rdt-result-pv-rectangular" {...props}></Icon>
