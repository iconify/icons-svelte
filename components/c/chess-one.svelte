<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r828l5b8c.css';
import '../../css/e/ept_tj7oo.css';
import '../../css/c/cy8y98b1l.css';
import '../../css/k/k_xqplfzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="r828l5b8c"/><path class="ept_tj7oo"/><path class="cy8y98b1l"/><path class="k_xqplfzx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:chess-one" {...props}></Icon>
