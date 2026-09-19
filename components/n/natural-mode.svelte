<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-rwuebrl.css';
import '../../css/x/xvzaotb_b.css';
import '../../css/g/g0av7_f0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="g-rwuebrl"><path class="xvzaotb_b"/><path class="g0av7_f0k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:natural-mode" {...props}></Icon>
