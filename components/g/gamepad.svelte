<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcoduql6c.css';
import '../../css/r/rdd3p3upc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jcoduql6c"/><path class="rdd3p3upc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:gamepad" {...props}></Icon>
