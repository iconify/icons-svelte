<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gkp0p4mnz.css';
import '../../css/x/xzckufbpo.css';
import '../../css/h/h4po3bbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gkp0p4mnz"/><path class="xzckufbpo"/><path class="h4po3bbim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-moon-rain" {...props}></Icon>
