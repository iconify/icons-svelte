<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrp-pcbtd.css';
import '../../css/e/evoi0uzhs.css';
import '../../css/k/k34k1_ice.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qrp-pcbtd"/><path class="evoi0uzhs"/><path class="k34k1_ice"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flywheel-20" {...props}></Icon>
