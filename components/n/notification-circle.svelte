<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/p/prunzyb5d.css';
import '../../css/w/w5_cz8xgt.css';
import '../../css/i/i8gugobaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="prunzyb5d"/><path class="w5_cz8xgt"/><path class="i8gugobaw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:notification-circle" {...props}></Icon>
