<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fp36hdbbo.css';
import '../../css/g/g626xxb-k.css';
import '../../css/d/dn272vvpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fp36hdbbo"/><path class="g626xxb-k"/><path class="dn272vvpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-top-right-linear" {...props}></Icon>
