<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/x/xrj1w3ubs.css';
import '../../css/e/e7-vbdckg.css';
import '../../css/b/b2n3vku2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsKv0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsKv0)"><path class="xrj1w3ubs"/><path class="e7-vbdckg"/><path class="b2n3vku2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:kv" {...props}></Icon>
