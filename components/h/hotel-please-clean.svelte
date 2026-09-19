<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w--pu8a5q.css';
import '../../css/e/ev65tbb2y.css';
import '../../css/f/f5p-36bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="w--pu8a5q"/><path class="ev65tbb2y"/><path class="f5p-36bbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hotel-please-clean" {...props}></Icon>
