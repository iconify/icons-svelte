<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mqoik2brt.css';
import '../../css/i/ixd5-yack.css';
import '../../css/a/axuwiubai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<g class="ft5dv1b6b"><path class="mqoik2brt"/><path class="ixd5-yack"/><path class="axuwiubai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cap" {...props}></Icon>
