<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md5fkyy9p.css';
import '../../css/w/ws35vdbar.css';
import '../../css/q/qcxo374xz.css';
import '../../css/o/ouybwccsi.css';
import '../../css/a/abxrhfy5t.css';
import '../../css/z/zmkur8bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="md5fkyy9p"/><path class="ws35vdbar"/><path class="qcxo374xz"/><g class="ouybwccsi"><path class="abxrhfy5t"/><path class="zmkur8bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:crayon" {...props}></Icon>
