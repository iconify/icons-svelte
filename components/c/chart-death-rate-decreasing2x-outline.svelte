<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/klv2o9buk.css';
import '../../css/l/l-6s2cixh.css';
import '../../css/t/terzj2bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="klv2o9buk"/><path clip-rule="evenodd" class="l-6s2cixh"/><path class="terzj2bry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-death-rate-decreasing2x-outline" {...props}></Icon>
