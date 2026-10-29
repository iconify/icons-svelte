<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/iem-hmb5q.css';
import '../../css/b/bxjv56brc.css';
import '../../css/f/fwfa9msgm.css';
import '../../css/s/s4mxkt2by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="iem-hmb5q wm-deco"/><path class="bxjv56brc wm-deco"/><path class="fwfa9msgm wm-k"/><path class="s4mxkt2by wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:filter-blueprint" {...props}></Icon>
