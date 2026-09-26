<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/q_3h0ub-d.css';
import '../../css/m/ml0cb1b5h.css';
import '../../css/s/shfdt_lyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q_3h0ub-d"/><path class="ml0cb1b5h"/><path class="shfdt_lyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-close-broken" {...props}></Icon>
