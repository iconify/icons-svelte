<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mghh_hb2u.css';
import '../../css/n/nltaw2slp.css';
import '../../css/l/l-2lalbbq.css';
import '../../css/e/e6kavsb1h.css';
import '../../css/d/d-hfqeb1l.css';
import '../../css/l/l-0p-ub1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mghh_hb2u"/><path class="nltaw2slp"/><path class="l-2lalbbq"/><path class="e6kavsb1h"/><path class="d-hfqeb1l"/><path class="l-0p-ub1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:icecream" {...props}></Icon>
