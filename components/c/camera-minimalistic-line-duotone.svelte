<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fr_tmn9fp.css';
import '../../css/z/zsm8mxmoo.css';
import '../../css/x/x4pob2bni.css';
import '../../css/l/lf-mtlb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="fr_tmn9fp"/><path class="zsm8mxmoo"/><path class="x4pob2bni"/><path class="lf-mtlb6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-minimalistic-line-duotone" {...props}></Icon>
