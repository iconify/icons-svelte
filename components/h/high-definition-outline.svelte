<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f2gxr5bwv.css';
import '../../css/x/xf6edy14c.css';
import '../../css/b/bbrv0_ogo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f2gxr5bwv"/><path clip-rule="evenodd" class="xf6edy14c"/><path clip-rule="evenodd" class="bbrv0_ogo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:high-definition-outline" {...props}></Icon>
