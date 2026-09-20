<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/z90fo5wsb.css';
import '../../css/m/m6oc2ft_g.css';
import '../../css/h/hfe67g-cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z90fo5wsb"/><path class="m6oc2ft_g"/><path class="hfe67g-cm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-plus" {...props}></Icon>
