<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rslo40inv.css';
import '../../css/r/rwsq_83pk.css';
import '../../css/w/warcgn-bq.css';
import '../../css/o/ov0_cbb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rslo40inv"/><path class="rwsq_83pk"/><path class="warcgn-bq"/><path class="ov0_cbb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:creditcard" {...props}></Icon>
