<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w--pu8a5q.css';
import '../../css/z/z93cypbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="w--pu8a5q"/><path class="z93cypbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hotel-do-not-clean" {...props}></Icon>
