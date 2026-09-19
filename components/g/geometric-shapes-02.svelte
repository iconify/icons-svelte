<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pz3scgbdp.css';
import '../../css/v/vy_h11b1c.css';
import '../../css/r/rwivxdqcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="pz3scgbdp"/><path class="vy_h11b1c"/><path class="rwivxdqcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:geometric-shapes-02" {...props}></Icon>
