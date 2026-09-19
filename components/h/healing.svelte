<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjkthvsjg.css';
import '../../css/q/qu789qgwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjkthvsjg"/><path class="qu789qgwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:healing" {...props}></Icon>
