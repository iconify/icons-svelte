<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mwn3f8bfu.css';
import '../../css/w/w1btr7zag.css';
import '../../css/d/dcq-5rbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="mwn3f8bfu"/><path clip-rule="evenodd" class="w1btr7zag"/><path class="dcq-5rbfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:pen-print" {...props}></Icon>
