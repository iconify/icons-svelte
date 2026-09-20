<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dtq3ihx1g.css';
import '../../css/z/zzr1xccry.css';
import '../../css/m/mat63ubej.css';
import '../../css/k/kem226bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dtq3ihx1g"/><path class="zzr1xccry"/><path class="mat63ubej"/><path class="kem226bqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cellular-network-wifi-4g" {...props}></Icon>
