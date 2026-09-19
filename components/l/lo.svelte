<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/k/ksy1gcbdc.css';
import '../../css/m/m-eozcb5y.css';
import '../../css/w/w75vgjb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsLo0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsLo0)"><path class="ksy1gcbdc"/><path class="m-eozcb5y"/><circle class="w75vgjb0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:lo" {...props}></Icon>
