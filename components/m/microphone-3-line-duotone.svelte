<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/guj5ndblb.css';
import '../../css/s/s8pml3bkm.css';
import '../../css/g/g3qc0bb8u.css';
import '../../css/n/nh-kspbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="guj5ndblb"/><path class="s8pml3bkm"/><path class="g3qc0bb8u"/><path class="nh-kspbph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:microphone-3-line-duotone" {...props}></Icon>
