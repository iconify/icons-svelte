<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bcgh91bjm.css';
import '../../css/f/fyr67fbfm.css';
import '../../css/n/nt3og-bhm.css';
import '../../css/i/iofcxjb4n.css';
import '../../css/g/gvinp5b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bcgh91bjm"/><path class="fyr67fbfm"/><path class="nt3og-bhm"/><path class="iofcxjb4n"/><path class="gvinp5b1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flash-drive-linear" {...props}></Icon>
