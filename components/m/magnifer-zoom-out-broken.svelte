<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kjxg36b_m.css';
import '../../css/c/cq5xp9n1p.css';
import '../../css/x/x09loybdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kjxg36b_m"/><path class="cq5xp9n1p"/><path class="x09loybdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifer-zoom-out-broken" {...props}></Icon>
