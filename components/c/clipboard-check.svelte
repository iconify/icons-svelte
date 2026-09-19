<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jzwkv4bnr.css';
import '../../css/i/ifj46hwma.css';
import '../../css/d/dalt38r3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jzwkv4bnr"/><path class="ifj46hwma"/><path clip-rule="evenodd" class="dalt38r3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:clipboard-check" {...props}></Icon>
