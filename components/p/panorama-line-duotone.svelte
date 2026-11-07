<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/ft-nr84oc.css';
import '../../css/z/zia4plbis.css';
import '../../css/x/xbt_tmtte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ft-nr84oc"/><path class="zia4plbis"/><path class="xbt_tmtte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panorama-line-duotone" {...props}></Icon>
