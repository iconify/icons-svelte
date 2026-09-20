<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/v/vj04c2bej.css';
import '../../css/e/e3ixk8zud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="vj04c2bej"/><path class="e3ixk8zud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:divide" {...props}></Icon>
