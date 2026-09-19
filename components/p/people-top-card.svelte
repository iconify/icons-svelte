<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/clsvsg_8u.css';
import '../../css/p/p4ycgacfu.css';
import '../../css/n/nzi04mbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="clsvsg_8u"/><circle class="p4ycgacfu"/><path class="nzi04mbzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-top-card" {...props}></Icon>
