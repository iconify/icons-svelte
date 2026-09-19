<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_tr_7bxk.css';
import '../../css/q/qks_3bc-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_tr_7bxk"/><path class="qks_3bc-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:filter-frames" {...props}></Icon>
