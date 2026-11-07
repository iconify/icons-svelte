<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/a8xienwaj.css';
import '../../css/q/qy44fxbnk.css';
import '../../css/o/oghfln6am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a8xienwaj"/><path class="qy44fxbnk"/><path class="oghfln6am"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-linear" {...props}></Icon>
