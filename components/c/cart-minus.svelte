<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7onm78_h.css';
import '../../css/t/t2k1y2acb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7onm78_h"/><path class="t2k1y2acb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-minus" {...props}></Icon>
