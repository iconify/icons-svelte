<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/ch_n9zb8m.css';
import '../../css/o/og7lw7bbb.css';
import '../../css/b/b4_rsjb-p.css';
import '../../css/o/ob35u0bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ch_n9zb8m"/><path class="og7lw7bbb"/><path class="b4_rsjb-p"/><path class="ob35u0bzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-stars-broken" {...props}></Icon>
