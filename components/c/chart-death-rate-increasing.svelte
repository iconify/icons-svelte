<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sb7r65ztw.css';
import '../../css/p/ptgid_4ay.css';
import '../../css/m/m89qgbkka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="sb7r65ztw"/><path clip-rule="evenodd" class="ptgid_4ay"/><path class="m89qgbkka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-death-rate-increasing" {...props}></Icon>
