<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hao-y3_km.css';
import '../../css/c/csp4cxb4v.css';
import '../../css/p/ptrg_gs-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hao-y3_km"/><path class="csp4cxb4v"/><path class="ptrg_gs-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-top-left-bold-duotone" {...props}></Icon>
