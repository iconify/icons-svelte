<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fu0daqcgv.css';
import '../../css/t/tnj11zbtt.css';
import '../../css/i/i-jb43rcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="ft5dv1b6b"><circle class="fu0daqcgv"/><path class="tnj11zbtt"/><path class="i-jb43rcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nimoxis" {...props}></Icon>
