<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iqwgs_b2i.css';
import '../../css/w/wk0l59qvo.css';
import '../../css/q/qs6p1db2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iqwgs_b2i"/><path class="wk0l59qvo"/><path class="qs6p1db2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-line-duotone" {...props}></Icon>
