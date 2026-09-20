<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuvplbckt.css';
import '../../css/n/n7ffj_asf.css';
import '../../css/c/crzhrw1pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vuvplbckt"/><path class="n7ffj_asf"/><path class="crzhrw1pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:centos" {...props}></Icon>
