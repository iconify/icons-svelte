<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/ubewop_6h.css';
import '../../css/q/qd654zb1j.css';
import '../../css/s/sc95x2bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="ubewop_6h"/><path class="qd654zb1j"/><path class="sc95x2bmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:buy" {...props}></Icon>
