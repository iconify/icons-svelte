<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/u/uvh5rrbvb.css';
import '../../css/f/f6-wovb1x.css';
import '../../css/q/qu-o3tbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><rect class="uvh5rrbvb"/><path class="f6-wovb1x"/><path class="qu-o3tbth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:mouse-one" {...props}></Icon>
