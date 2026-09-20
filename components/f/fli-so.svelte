<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bov0584ws.css';
import '../../css/p/pcybz4e1f.css';
import '../../css/s/skc1clb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bov0584ws"/><path class="pcybz4e1f"/><path class="skc1clb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fli-so" {...props}></Icon>
