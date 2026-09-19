<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c4wfglb7q.css';
import '../../css/d/datb84q6e.css';
import '../../css/m/m9i7a_vaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="c4wfglb7q"/><path class="datb84q6e"/><path class="m9i7a_vaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-chart-pie" {...props}></Icon>
