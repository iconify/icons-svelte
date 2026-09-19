<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/k/knbkhybae.css';
import '../../css/p/pxs4cphfa.css';
import '../../css/j/jj_owxbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="knbkhybae"/><path class="pxs4cphfa"/><path class="jj_owxbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:cr-4x3" {...props}></Icon>
