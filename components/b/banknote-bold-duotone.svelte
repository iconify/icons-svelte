<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nwzadmbzz.css';
import '../../css/i/ikjivy1kl.css';
import '../../css/y/yaqpnvgfb.css';
import '../../css/a/a2owrl2nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nwzadmbzz"/><path class="ikjivy1kl"/><path class="yaqpnvgfb"/><path clip-rule="evenodd" class="a2owrl2nd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:banknote-bold-duotone" {...props}></Icon>
