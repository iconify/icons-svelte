<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xw37gnbno.css';
import '../../css/l/lan_z0x-a.css';
import '../../css/a/aqcce2f6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="xw37gnbno"/><path class="lan_z0x-a"/><circle class="aqcce2f6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:lock-open" {...props}></Icon>
