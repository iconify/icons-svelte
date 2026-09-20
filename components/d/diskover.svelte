<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n56ae_bgb.css';
import '../../css/j/jigbsmb_n.css';
import '../../css/l/l2vhs6x9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n56ae_bgb"/><path class="jigbsmb_n"/><path class="l2vhs6x9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:diskover" {...props}></Icon>
