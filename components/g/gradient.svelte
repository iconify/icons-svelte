<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx-_r7b2v.css';
import '../../css/v/vam_rybkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tx-_r7b2v"/><path class="vam_rybkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:gradient" {...props}></Icon>
