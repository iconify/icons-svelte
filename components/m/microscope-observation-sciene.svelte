<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vvo_4lblf.css';
import '../../css/g/gxnd-ryzh.css';
import '../../css/i/iphl04buv.css';
import '../../css/v/vlgnrqtjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vvo_4lblf"/><path class="gxnd-ryzh"/><path class="iphl04buv"/><path class="vlgnrqtjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:microscope-observation-sciene" {...props}></Icon>
