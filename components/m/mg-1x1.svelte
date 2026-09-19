<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/f/f98f8evyn.css';
import '../../css/n/nsqla6jpd.css';
import '../../css/w/wps4e9ynm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="nv9qcacyl"><path class="f98f8evyn"/><path class="nsqla6jpd"/><path class="wps4e9ynm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mg-1x1" {...props}></Icon>
