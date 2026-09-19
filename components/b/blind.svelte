<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfo-7vb2n.css';
import '../../css/t/tcdvgs_6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qfo-7vb2n"/><path class="tcdvgs_6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:blind" {...props}></Icon>
