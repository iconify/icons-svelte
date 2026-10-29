<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/sdo3s5gsn.css';
import '../../css/g/g91qa5pir.css';
import '../../css/m/mx2e90gcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="sdo3s5gsn"/><path class="g91qa5pir wm-a"/><path class="mx2e90gcg wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:briefcase-business-solid" {...props}></Icon>
