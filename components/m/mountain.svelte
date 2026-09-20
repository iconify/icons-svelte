<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/i/iig1o2bkc.css';
import '../../css/h/hmtd5ibay.css';
import '../../css/o/ogtgwab_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="iig1o2bkc"/><path class="hmtd5ibay"/><path class="ogtgwab_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:mountain" {...props}></Icon>
