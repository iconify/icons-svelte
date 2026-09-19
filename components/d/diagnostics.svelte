<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pajftwqsn.css';
import '../../css/s/s9c5dfbyd.css';
import '../../css/t/tny-dy4ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="pajftwqsn"/><path clip-rule="evenodd" class="s9c5dfbyd"/><path clip-rule="evenodd" class="tny-dy4ya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:diagnostics" {...props}></Icon>
