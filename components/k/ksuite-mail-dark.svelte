<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfv7kibpo.css';
import '../../css/d/dfc5wbcbr.css';
import '../../css/u/u_l71ebni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mfv7kibpo"/><path class="dfc5wbcbr"/><path class="u_l71ebni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-mail-dark" {...props}></Icon>
