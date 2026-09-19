<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yr9lhub6p.css';
import '../../css/l/l-6s2cixh.css';
import '../../css/t/terzj2bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="yr9lhub6p"/><path clip-rule="evenodd" class="l-6s2cixh"/><path class="terzj2bry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-death-rate-decreasing" {...props}></Icon>
