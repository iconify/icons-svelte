<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt1vj9bim.css';
import '../../css/m/mi5_bgb0n.css';
import '../../css/n/nxeppyb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pt1vj9bim"/><path class="mi5_bgb0n"/><path class="nxeppyb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:envoy" {...props}></Icon>
