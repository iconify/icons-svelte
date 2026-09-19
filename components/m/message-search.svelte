<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/j/jctm5acci.css';
import '../../css/b/bzyfhwhwi.css';
import '../../css/n/n67jz7bok.css';
import '../../css/h/hv9dsxbbr.css';
import '../../css/p/p1b-dvsdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="jctm5acci"/><circle class="bzyfhwhwi"/><path class="n67jz7bok"/><path class="hv9dsxbbr"/><path class="p1b-dvsdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:message-search" {...props}></Icon>
