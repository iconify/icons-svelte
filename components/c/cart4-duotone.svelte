<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z9fy4wczv.css';
import '../../css/k/k5xzmd8wb.css';
import '../../css/a/awo1ve8ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z9fy4wczv"/><path clip-rule="evenodd" class="k5xzmd8wb"/><path class="awo1ve8ww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart4-duotone" {...props}></Icon>
