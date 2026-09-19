<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaku_ef4i.css';
import '../../css/r/rk8kk9b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qaku_ef4i"/><path class="rk8kk9b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:fire" {...props}></Icon>
