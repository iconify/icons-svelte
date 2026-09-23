<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy0-wxbjy.css';
import '../../css/n/n3_4b3b1z.css';
import '../../css/l/l2_1s-n1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="fy0-wxbjy"><path class="n3_4b3b1z"/><path class="l2_1s-n1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nowly" {...props}></Icon>
