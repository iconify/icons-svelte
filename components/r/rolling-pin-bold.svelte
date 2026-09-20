<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pmwvltbwu.css';
import '../../css/b/bso_8zbol.css';
import '../../css/c/cbkt77dxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pmwvltbwu"/><path class="bso_8zbol"/><path class="cbkt77dxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rolling-pin-bold" {...props}></Icon>
