<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/bsh7occcx.css';
import '../../css/d/dv-f5_bfs.css';
import '../../css/i/iedi-yb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="bsh7occcx wm-shadow"/><path class="dv-f5_bfs wm-shadow"/><path class="iedi-yb1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:chart-column-stacked" {...props}></Icon>
