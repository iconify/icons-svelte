<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfn3-2b2h.css';
import '../../css/m/mgaiuk4dq.css';
import '../../css/e/e9665qbwc.css';
import '../../css/x/x21x2pqay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nfn3-2b2h"/><path class="mgaiuk4dq"/><path class="e9665qbwc"/><path class="x21x2pqay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:latex" {...props}></Icon>
