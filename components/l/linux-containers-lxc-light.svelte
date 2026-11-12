<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wap4fu7vn.css';
import '../../css/m/mex95lw7c.css';
import '../../css/m/mcdgwguil.css';
import '../../css/h/hh45kun6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wap4fu7vn"/><path class="mex95lw7c"/><path class="mcdgwguil"/><path class="hh45kun6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linux-containers-lxc-light" {...props}></Icon>
