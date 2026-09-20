<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy2u80b4g.css';
import '../../css/k/kk1809b4e.css';
import '../../css/z/zcl8rmben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oy2u80b4g"/><path class="kk1809b4e"/><path class="zcl8rmben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoiceplane" {...props}></Icon>
