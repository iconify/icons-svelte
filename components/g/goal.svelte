<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/e/eh8po51gx.css';
import '../../css/k/k0tem2btx.css';
import '../../css/o/ofonheb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="eh8po51gx"/><path class="k0tem2btx"/><path class="ofonheb_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:goal" {...props}></Icon>
