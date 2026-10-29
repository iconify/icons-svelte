<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/yaljho52x.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/p/pq0fz3bmd.css';
import '../../css/v/vaib7gbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco yaljho52x"/><path class="cf3uzcrzx wm-deco"/><path class="pq0fz3bmd"/><path class="vaib7gbcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-blueprint" {...props}></Icon>
