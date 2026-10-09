<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx2xmtbjn.css';
import '../../css/l/lajtdm1vq.css';
import '../../css/w/whg_zqbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xx2xmtbjn"/><path class="lajtdm1vq"/><path class="whg_zqbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-square-48" {...props}></Icon>
