<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/icewmop0r.css';
import '../../css/m/m8url67bk.css';
import '../../css/q/qohqnvbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="icewmop0r"/><path class="m8url67bk"/><path class="qohqnvbfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:doctor-female" {...props}></Icon>
