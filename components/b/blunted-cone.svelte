<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/g/g9jq30rox.css';
import '../../css/r/rkzp9kwbv.css';
import '../../css/m/mi9-umnto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="g9jq30rox"/><path class="rkzp9kwbv"/><path class="mi9-umnto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:blunted-cone" {...props}></Icon>
