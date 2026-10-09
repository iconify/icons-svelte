<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd85o-qpc.css';
import '../../css/l/l4lrodbjn.css';
import '../../css/b/bn5sk2bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qd85o-qpc"/><path class="l4lrodbjn"/><path class="bn5sk2bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:igloo-48" {...props}></Icon>
