<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lf0becbdq.css';
import '../../css/m/muxlfbbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":456,"height":456};
const content = `<g class="ft5dv1b6b"><path class="lf0becbdq"/><path class="muxlfbbte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:microsoft-dotnet" {...props}></Icon>
