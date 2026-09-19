<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wrm4btbfp.css';
import '../../css/c/cua4t8b_t.css';
import '../../css/u/usb15cc2i.css';
import '../../css/c/cy8y98b1l.css';
import '../../css/k/k_xqplfzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="wrm4btbfp"/><path class="cua4t8b_t"/><path class="usb15cc2i"/><path class="cy8y98b1l"/><path class="k_xqplfzx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:chess-one" {...props}></Icon>
