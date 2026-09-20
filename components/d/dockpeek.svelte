<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvr4ljncy.css';
import '../../css/q/qf_fqfblh.css';
import '../../css/s/sopu2lbmd.css';
import '../../css/r/rksq5bbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="uvr4ljncy"/><path class="qf_fqfblh"/><path class="sopu2lbmd"/><circle class="rksq5bbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockpeek" {...props}></Icon>
