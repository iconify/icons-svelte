<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/ddnvz1tnc.css';
import '../../css/g/gdp166b8a.css';
import '../../css/p/pb3f6qbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ddnvz1tnc wm-k"/><path class="gdp166b8a wm-shine"/><path class="pb3f6qbdb wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:book-open-text" {...props}></Icon>
