<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kjxg36b_m.css';
import '../../css/x/xtutonbhb.css';
import '../../css/x/x09loybdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kjxg36b_m"/><path class="xtutonbhb"/><path class="x09loybdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifer-zoom-in-broken" {...props}></Icon>
