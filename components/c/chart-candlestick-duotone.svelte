<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/drq9pyb0s.css';
import '../../css/c/cza6ut-na.css';
import '../../css/s/slcgv9bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="drq9pyb0s"/><path class="cza6ut-na"/><path class="slcgv9bsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-candlestick-duotone" {...props}></Icon>
