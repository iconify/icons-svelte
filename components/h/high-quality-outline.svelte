<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nxkw0pebi.css';
import '../../css/f/f1vp1rstx.css';
import '../../css/b/bbrv0_ogo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nxkw0pebi"/><path class="f1vp1rstx"/><path clip-rule="evenodd" class="bbrv0_ogo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:high-quality-outline" {...props}></Icon>
