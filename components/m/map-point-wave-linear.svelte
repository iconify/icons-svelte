<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uh8evbbul.css';
import '../../css/v/vv52kbcqz.css';
import '../../css/q/qq--gqc6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uh8evbbul"/><path class="vv52kbcqz"/><path class="qq--gqc6p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-wave-linear" {...props}></Icon>
