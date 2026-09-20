<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dw3gp6vcm.css';
import '../../css/n/na80fjbih.css';
import '../../css/y/ywpq_rvvt.css';
import '../../css/p/p6o9-vebo.css';
import '../../css/p/po5h2dbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dw3gp6vcm"/><path class="na80fjbih"/><path class="ywpq_rvvt"/><path class="p6o9-vebo"/><path class="po5h2dbat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-full-line-duotone" {...props}></Icon>
