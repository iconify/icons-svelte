<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kntji4pqg.css';
import '../../css/e/e8i5ctbbw.css';
import '../../css/x/xo8rjg3rh.css';
import '../../css/x/xw_tiwbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kntji4pqg"/><path clip-rule="evenodd" class="e8i5ctbbw"/><path class="xo8rjg3rh"/><path class="xw_tiwbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:album-bold" {...props}></Icon>
