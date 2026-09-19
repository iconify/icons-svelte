<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kqvem9u7e.css';
import '../../css/i/iqdcki20w.css';
import '../../css/v/vsy6rtmax.css';
import '../../css/i/i7b6h4s-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kqvem9u7e"/><path clip-rule="evenodd" class="iqdcki20w"/><path clip-rule="evenodd" class="vsy6rtmax"/><path class="i7b6h4s-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:dress-print" {...props}></Icon>
