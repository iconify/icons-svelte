<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/k/ke9wffmav.css';
import '../../css/d/dr5ltpb6s.css';
import '../../css/q/qx_x0ac8s.css';
import '../../css/b/bz1c17bfk.css';
import '../../css/c/c9r91ziyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ke9wffmav wm-shadow"/><path class="dr5ltpb6s wm-shadow"/><path class="qx_x0ac8s"/><path class="bz1c17bfk"/><path class="c9r91ziyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:cable" {...props}></Icon>
