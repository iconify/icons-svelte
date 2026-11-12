<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlsi6_kti.css';
import '../../css/n/njlpr9bmf.css';
import '../../css/q/qbc0ipycg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xlsi6_kti"/><path class="njlpr9bmf"/><path class="qbc0ipycg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-grids-light" {...props}></Icon>
