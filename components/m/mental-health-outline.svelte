<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/swx8fsbua.css';
import '../../css/n/nmq3ynjwh.css';
import '../../css/s/sknk2ccfl.css';
import '../../css/v/v5e_qsmla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="swx8fsbua"/><path clip-rule="evenodd" class="nmq3ynjwh"/><path class="sknk2ccfl"/><path clip-rule="evenodd" class="v5e_qsmla"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mental-health-outline" {...props}></Icon>
