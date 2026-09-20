<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/doy9q4b5f.css';
import '../../css/g/gwtb9fb5e.css';
import '../../css/p/p3a3-wxlk.css';
import '../../css/p/p9ekrnbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="gwtb9fb5e"/><path class="p3a3-wxlk"/><path class="p9ekrnbem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dollar-minimalistic-line-duotone" {...props}></Icon>
