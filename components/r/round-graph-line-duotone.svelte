<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kj9125bhw.css';
import '../../css/u/ubsyz0bji.css';
import '../../css/a/a09g2ehcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kj9125bhw"/><path class="ubsyz0bji"/><path class="a09g2ehcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-graph-line-duotone" {...props}></Icon>
