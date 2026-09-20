<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/dh7z03bvs.css';
import '../../css/t/tthwrtzkx.css';
import '../../css/r/rt4cydqwb.css';
import '../../css/x/xhm_tdbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dh7z03bvs"/><path class="tthwrtzkx"/><circle class="rt4cydqwb"/><rect class="xhm_tdbwp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:images" {...props}></Icon>
