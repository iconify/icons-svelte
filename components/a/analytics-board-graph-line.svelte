<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uzrxcz3ph.css';
import '../../css/r/rdkkd29wn.css';
import '../../css/n/nw0p1ubxk.css';
import '../../css/y/ydek3pbkk.css';
import '../../css/f/frma-obdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uzrxcz3ph"/><path class="rdkkd29wn"/><path class="nw0p1ubxk"/><path class="ydek3pbkk"/><path class="frma-obdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:analytics-board-graph-line" {...props}></Icon>
