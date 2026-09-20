<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xyjtgccot.css';
import '../../css/d/dd8bl5bbm.css';
import '../../css/z/z7psoab5m.css';
import '../../css/e/e4aw4xbir.css';
import '../../css/f/fmg0zibqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="xyjtgccot"><path class="dd8bl5bbm"/><path clip-rule="evenodd" class="z7psoab5m"/></g><path clip-rule="evenodd" class="e4aw4xbir"/><path clip-rule="evenodd" class="fmg0zibqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:floppy-disk" {...props}></Icon>
