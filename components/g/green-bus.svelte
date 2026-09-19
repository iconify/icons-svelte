<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k4nc1v0sz.css';
import '../../css/b/btywncb6s.css';
import '../../css/f/f3sds_beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k4nc1v0sz"/><path class="btywncb6s"/><path class="f3sds_beg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:green-bus" {...props}></Icon>
