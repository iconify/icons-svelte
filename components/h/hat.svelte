<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/o3y-mwb9w.css';
import '../../css/k/keebtzb8q.css';
import '../../css/f/fi8jscb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="o3y-mwb9w"/><rect class="keebtzb8q"/><path class="fi8jscb1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:hat" {...props}></Icon>
