<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwpcakq3y.css';
import '../../css/h/h0r0o6bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwpcakq3y"/><path class="h0r0o6bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:battery-3" {...props}></Icon>
