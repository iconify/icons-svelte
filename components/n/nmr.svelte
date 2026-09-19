<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vkcj4bcdm.css';
import '../../css/j/j49yvvine.css';
import '../../css/o/og4ylxbsv.css';
import '../../css/y/y72c0qhnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vkcj4bcdm"/><path class="j49yvvine"/><path class="og4ylxbsv"/><path class="y72c0qhnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:nmr" {...props}></Icon>
