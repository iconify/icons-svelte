<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/raj4z-pfe.css';
import '../../css/l/lx0j_nfbx.css';
import '../../css/i/iyxxnubym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="raj4z-pfe"/><path class="lx0j_nfbx"/><path class="iyxxnubym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoiceplane-light" {...props}></Icon>
