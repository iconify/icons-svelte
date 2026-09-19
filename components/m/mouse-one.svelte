<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/uvh5rrbvb.css';
import '../../css/s/scdv35xyn.css';
import '../../css/s/sjya5bbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="uvh5rrbvb"/><path class="scdv35xyn"/><path class="sjya5bbyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:mouse-one" {...props}></Icon>
