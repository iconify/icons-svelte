<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eg6ampbwl.css';
import '../../css/f/fx9knvb4h.css';
import '../../css/c/cmpm5kb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="eg6ampbwl"/><path class="fx9knvb4h"/><path clip-rule="evenodd" class="cmpm5kb0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-o-p" {...props}></Icon>
