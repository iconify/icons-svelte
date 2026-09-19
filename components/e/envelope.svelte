<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsmu98p6c.css';
import '../../css/h/hs-tb-btz.css';
import '../../css/m/mc75m8d8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="xsmu98p6c"/><path class="hs-tb-btz"/><path class="mc75m8d8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:envelope" {...props}></Icon>
