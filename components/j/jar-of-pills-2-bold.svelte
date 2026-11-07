<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqhsul-mi.css';
import '../../css/r/rg6jpcctx.css';
import '../../css/h/hn9kuubay.css';
import '../../css/i/ioy2u6bps.css';
import '../../css/b/bqzidgs3h.css';
import '../../css/n/nrkqveb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqhsul-mi"/><path class="rg6jpcctx"/><path class="hn9kuubay"/><path clip-rule="evenodd" class="ioy2u6bps"/><path class="bqzidgs3h"/><path class="nrkqveb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:jar-of-pills-2-bold" {...props}></Icon>
