<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u50gi_bex.css';
import '../../css/m/mw42pob4d.css';
import '../../css/p/pqorf1bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u50gi_bex"/><path class="mw42pob4d"/><path class="pqorf1bzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-music-line-duotone" {...props}></Icon>
