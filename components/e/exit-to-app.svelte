<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmx2n3bsv.css';
import '../../css/k/k0e30mbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmx2n3bsv"/><path class="k0e30mbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:exit-to-app" {...props}></Icon>
