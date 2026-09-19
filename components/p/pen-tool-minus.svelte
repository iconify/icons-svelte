<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p9pv0vbyl.css';
import '../../css/f/fxex-8b8d.css';
import '../../css/g/g2bflsbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p9pv0vbyl"/><path class="fxex-8b8d"/><path class="g2bflsbhg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pen-tool-minus" {...props}></Icon>
