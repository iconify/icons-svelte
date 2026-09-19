<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/z/zd1deebgz.css';
import '../../css/w/w8aqjtb4l.css';
import '../../css/y/y8q-dtbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="zd1deebgz"/><path class="w8aqjtb4l"/><ellipse class="y8q-dtbfz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:data" {...props}></Icon>
