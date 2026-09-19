<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/e/e8yohmb3w.css';
import '../../css/m/me1_ckb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsEl0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsEl0)"><path class="e8yohmb3w"/><path class="me1_ckb-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:el" {...props}></Icon>
