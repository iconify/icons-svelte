<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ai2w0-bae.css';
import '../../css/e/egr1ps-7z.css';
import '../../css/g/g38ojablm.css';
import '../../css/c/cd2dae1lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ai2w0-bae"/><path class="egr1ps-7z"/><path clip-rule="evenodd" class="g38ojablm"/><path class="cd2dae1lh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:coughing-outline-24px" {...props}></Icon>
