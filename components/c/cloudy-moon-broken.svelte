<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kod-jwb_a.css';
import '../../css/l/lc-1m4bvp.css';
import '../../css/e/e78qg7bkf.css';
import '../../css/m/mvo7t3bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kod-jwb_a"/><path class="lc-1m4bvp"/><path class="e78qg7bkf"/><path class="mvo7t3bjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloudy-moon-broken" {...props}></Icon>
