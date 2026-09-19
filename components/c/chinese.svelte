<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/l/ljdas5boi.css';
import '../../css/e/e74gmob1x.css';
import '../../css/r/ragiu_dif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="gopnm44um"><rect class="ljdas5boi"/><rect class="e74gmob1x"/><path class="ragiu_dif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:chinese" {...props}></Icon>
