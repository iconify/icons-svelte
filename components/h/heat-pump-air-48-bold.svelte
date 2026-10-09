<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mokpnsr8g.css';
import '../../css/h/ha9ji7bbv.css';
import '../../css/l/lo-76q32a.css';
import '../../css/j/jo56bbk_e.css';
import '../../css/m/mhiv-6b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mokpnsr8g"/><path class="ha9ji7bbv"/><path class="lo-76q32a"/><path class="jo56bbk_e"/><path class="mhiv-6b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-air-48-bold" {...props}></Icon>
