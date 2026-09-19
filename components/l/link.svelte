<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuipojbnc.css';
import '../../css/m/mxlj29bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nuipojbnc"/><path class="mxlj29bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:link" {...props}></Icon>
