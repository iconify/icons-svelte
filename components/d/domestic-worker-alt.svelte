<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ixbft3bvx.css';
import '../../css/p/pe-vqcblg.css';
import '../../css/v/vm02urlpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ixbft3bvx"/><path clip-rule="evenodd" class="pe-vqcblg"/><path class="vm02urlpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:domestic-worker-alt" {...props}></Icon>
