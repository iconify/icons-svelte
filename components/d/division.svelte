<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/knq66i4mf.css';
import '../../css/o/owghvwb3e.css';
import '../../css/j/jxsnms7hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="knq66i4mf"/><circle class="owghvwb3e"/><path class="jxsnms7hz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:division" {...props}></Icon>
