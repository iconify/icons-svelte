<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/ttsgbty3f.css';
import '../../css/r/rkn7cdc2p.css';
import '../../css/m/mow6e1kbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ttsgbty3f"/><path class="rkn7cdc2p"/><path clip-rule="evenodd" class="mow6e1kbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:coughing-alt-outline" {...props}></Icon>
