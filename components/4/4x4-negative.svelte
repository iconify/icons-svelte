<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fuy0zyboz.css';
import '../../css/d/dyzl-zbur.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthicons4x4Negative0)" class="cuyn6tgcc"><path class="fuy0zyboz"/><path clip-rule="evenodd" class="dyzl-zbur"/></g><defs><clipPath id="healthicons4x4Negative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:4x4-negative" {...props}></Icon>
