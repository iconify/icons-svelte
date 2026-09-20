<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wrski3b_o.css';
import '../../css/q/qzritzb0s.css';
import '../../css/k/kga3h3bmu.css';
import '../../css/x/xypkzkhmd.css';
import '../../css/s/si_mtzbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wrski3b_o"/><path class="qzritzb0s"/><path class="kga3h3bmu"/><path class="xypkzkhmd"/><path class="si_mtzbvj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:branching-paths-down-broken" {...props}></Icon>
