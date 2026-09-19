<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt5pyeboi.css';
import '../../css/n/njpxlezen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mt5pyeboi"/><path class="njpxlezen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ansible" {...props}></Icon>
