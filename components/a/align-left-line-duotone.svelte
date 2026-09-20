<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oc4beac5y.css';
import '../../css/r/rr1ygbacx.css';
import '../../css/o/oh-ffpj9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oc4beac5y"/><path class="rr1ygbacx"/><path class="oh-ffpj9g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-left-line-duotone" {...props}></Icon>
