<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0dchj1_o.css';
import '../../css/n/n0n3q2bzz.css';
import '../../css/n/nck3jf4bf.css';
import '../../css/t/tfdeh6r_u.css';
import '../../css/w/w_v5gjbli.css';
import '../../css/m/mvfn51b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g0dchj1_o"/><path class="n0n3q2bzz"/><path class="nck3jf4bf"/><path class="tfdeh6r_u"/><path class="w_v5gjbli"/><path class="mvfn51b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ram" {...props}></Icon>
