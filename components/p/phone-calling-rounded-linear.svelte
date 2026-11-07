<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bucfw6bdg.css';
import '../../css/q/qy44fxbnk.css';
import '../../css/n/n2z2bb1zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bucfw6bdg"/><path class="qy44fxbnk"/><path class="n2z2bb1zb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-rounded-linear" {...props}></Icon>
