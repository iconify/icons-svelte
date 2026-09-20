<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y9e2kcbuv.css';
import '../../css/k/k774yynor.css';
import '../../css/d/dnka95bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y9e2kcbuv"/><path class="k774yynor"/><path class="dnka95bah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-3-bold-duotone" {...props}></Icon>
