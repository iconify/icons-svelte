<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z22a7qbic.css';
import '../../css/d/dpjj_cbbf.css';
import '../../css/l/lhks2kb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a z22a7qbic"/><path class="dpjj_cbbf wm-k"/><path class="lhks2kb_g wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chart-area" {...props}></Icon>
