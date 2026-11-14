<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oirotweno.css';
import '../../css/d/d9fwxhphv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oirotweno"/><path class="d9fwxhphv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-hole-dark" {...props}></Icon>
