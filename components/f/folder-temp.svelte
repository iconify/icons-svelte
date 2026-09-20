<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7-c3zb9h.css';
import '../../css/r/rg12uoqrx.css';
import '../../css/z/ze5omzbef.css';
import '../../css/c/c23j0pb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v7-c3zb9h"/><g class="rg12uoqrx"><path class="ze5omzbef"/><path class="c23j0pb_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-temp" {...props}></Icon>
