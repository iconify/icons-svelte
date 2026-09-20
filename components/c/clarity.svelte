<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3doyjoii.css';
import '../../css/m/mf9jpj7oz.css';
import '../../css/t/t4s-b1bpo.css';
import '../../css/t/te7q60mep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l3doyjoii"/><path class="mf9jpj7oz"/><path class="t4s-b1bpo"/><path class="te7q60mep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:clarity" {...props}></Icon>
