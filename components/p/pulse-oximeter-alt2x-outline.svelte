<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k22u013fs.css';
import '../../css/t/t-_-0-bda.css';
import '../../css/f/fqe8gmnza.css';
import '../../css/q/q0dvfvbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="k22u013fs"/><path clip-rule="evenodd" class="t-_-0-bda"/><path class="fqe8gmnza"/><path clip-rule="evenodd" class="q0dvfvbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pulse-oximeter-alt2x-outline" {...props}></Icon>
