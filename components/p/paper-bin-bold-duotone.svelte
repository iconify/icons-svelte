<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h0_3y9-wd.css';
import '../../css/e/ed8ehg-oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h0_3y9-wd"/><path clip-rule="evenodd" class="ed8ehg-oy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paper-bin-bold-duotone" {...props}></Icon>
